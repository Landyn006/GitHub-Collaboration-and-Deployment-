 GitHub Actions Workflow Analysis

1. What events trigger this workflow?

The workflow is triggered when code is pushed to the `main` branch or when a pull request is opened or updated against the `main` branch.

The workflow uses:

- `push` to `main`
- `pull_request` to `main`

2. What are the four main steps in the workflow?

The main steps in the build-and-test job are:

1. Checkout code
2. Validate HTML
3. Check links
4. Upload artifact

After the build-and-test job succeeds, the deploy job deploys the website to GitHub Pages.

 3. What does the "Checkout code" step do?

The Checkout code step uses the `actions/checkout@v4` action to download the repository's code into the GitHub Actions runner. This allows the other workflow steps to access and test the website files.

 4. What is the purpose of the environment configuration?

The environment configuration sets the deployment environment to `github-pages` and provides the URL for the deployed website. It also works with the permissions needed for GitHub Pages deployment.

5. How does this workflow improve reliability compared to manual deployment?

The workflow improves reliability by automatically checking the website whenever changes are pushed or a pull request is made. It validates the HTML, checks links, and creates the deployment artifact automatically. This reduces the chance of forgetting a testing or deployment step when updating the website.

6. What happens when changes are made on a non-main branch?

When changes are made on a non-main branch and a pull request is created toward `main`, the build-and-test job runs so the changes can be checked. The workflow validates the HTML, checks links, and creates the deployment artifact. However, the deployment job does not run because it is only allowed when the workflow is triggered by a push to the `main` branch. This helps prevent unfinished feature branches from being deployed to the live website.