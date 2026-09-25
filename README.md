# TechFlow Solutions Website

[![Deploy to GitHub Pages](https://github.com/Landyn006/GitHub-Collaboration-and-Deployment-/actions/workflows/deploy.yml/badge.svg)](https://github.com/Landyn006/GitHub-Collaboration-and-Deployment-/actions/workflows/deploy.yml)

A modern, fully responsive website for **TechFlow Solutions** — a web development company specializing in custom, high-quality websites for small businesses. This project demonstrates professional web development practices, automated CI/CD deployment, and collaborative Git workflows.

## 📋 Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Development Workflow](#development-workflow)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **Responsive Design**: Seamlessly adapts to desktop, tablet, and mobile devices
- **Modern UI**: Professional, clean design with smooth animations and transitions
- **Interactive Contact Form**: Fully functional form with client-side validation
- **Smooth Navigation**: Fixed header with smooth scroll-to-section functionality
- **Performance Optimized**: Lightweight, fast-loading pages
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility
- **Automated Deployment**: GitHub Actions workflow for continuous deployment to GitHub Pages

## 🛠 Technologies

| Technology | Purpose | Details |
|---|---|---|
| **HTML5** | Markup & Structure | Semantic HTML with proper accessibility |
| **CSS3** | Styling & Layout | Flexbox, CSS Grid, Media Queries, Animations |
| **JavaScript (ES6+)** | Interactivity | Vanilla JS, no dependencies; form validation & smooth scrolling |
| **GitHub Actions** | CI/CD Pipeline | Automated testing and deployment to GitHub Pages |

## 📁 Project Structure

```
GitHub-Collaboration-and-Deployment-/
├── index.html              # Main website HTML
├── styles.css              # Stylesheet with responsive design
├── script.js               # JavaScript for interactivity
├── README.md               # Project documentation
├── WORKFLOW_ANALYSIS.md    # GitHub Actions workflow documentation
└── .github/
    └── workflows/
        └── deploy.yml      # Automated deployment workflow
```

**Language Composition:**
- HTML: 52%
- CSS: 37.4%
- JavaScript: 10.6%

## 🚀 Installation

### Prerequisites

- **Git** installed on your local machine
- **Modern web browser** (Chrome, Firefox, Safari, or Edge)
- **Text editor** (VS Code recommended)

### Local Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Landyn006/GitHub-Collaboration-and-Deployment-.git
   cd GitHub-Collaboration-and-Deployment-
   ```

2. **Open in your text editor:**
   ```bash
   code .
   ```

3. **View locally:**
   - Open `index.html` directly in your browser, or
   - Use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

## 💻 Usage

### Viewing the Website

1. **Local Development:**
   - Launch the local server (see Installation)
   - Navigate to `http://localhost:8000` in your browser
   - Test all features: navigation, contact form, and responsiveness

2. **Testing Responsiveness:**
   - Open DevTools (F12 or Cmd+Option+I)
   - Toggle Device Toolbar to test tablet and mobile views
   - Verify all sections load and function correctly

### Making Changes

1. **Create a feature branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Edit files in your text editor:**
   - Modify `index.html` for structure changes
   - Update `styles.css` for styling
   - Add functionality in `script.js`

3. **Test locally:**
   - Refresh your browser to see changes
   - Test on multiple screen sizes
   - Verify form validation works

4. **Commit and push:**
   ```bash
   git add .
   git commit -m "Add: descriptive message of your changes"
   git push origin feature/your-feature-name
   ```

5. **Create a Pull Request:**
   - Push your changes to GitHub
   - Navigate to the repository
   - Click "Compare & pull request"
   - Add a descriptive title and description
   - Request review from team members

6. **After approval:**
   - Merge the pull request to `main`
   - GitHub Actions automatically deploys to GitHub Pages

## 🌐 Deployment

### Automatic Deployment

This project uses **GitHub Actions** for continuous integration and deployment:

1. **Trigger:** When code is pushed to the `main` branch
2. **Process:** GitHub Actions runs the `deploy.yml` workflow
3. **Deployment:** Website is automatically published to GitHub Pages

### GitHub Pages Configuration

- **Repository Settings** → **Pages**
- **Source:** Deploy from a branch
- **Branch:** `main` / root directory
- **Live URL:** `https://Landyn006.github.io/GitHub-Collaboration-and-Deployment-/`

### Checking Deployment Status

1. Go to **Actions** tab in your repository
2. View the latest workflow run
3. Check logs for any build errors
4. Once passed ✅, changes are live on GitHub Pages

## 🔄 Development Workflow

This project follows professional development practices:

### Branching Strategy
- **main:** Production-ready code, protected branch
- **feature/\*:** Feature branches for new functionality
- Each feature gets its own branch and pull request

### Code Review Process
1. Create a pull request with clear description
2. Team members review the code
3. Address feedback and make requested changes
4. Approval required before merging
5. Automatic deployment after merge to main

### Best Practices
- Write descriptive commit messages
- Keep commits atomic and focused
- Test changes locally before pushing
- Request reviews from teammates
- Use meaningful branch names

## 👥 Contributing

This is an educational project for practicing collaborative development workflows. To contribute:

1. Follow the branching strategy (create a feature branch)
2. Make your changes and test thoroughly
3. Commit with clear, descriptive messages
4. Push your branch and create a pull request
5. Include a summary of changes in the PR description
6. Address any review feedback
7. Merge after approval

For detailed workflow instructions, see the assignment guidelines.

## 📄 License

This project is for educational purposes.

---

<div align="center">

**Built with ❤️ by the TechFlow Solutions team**

[Live Site](https://Landyn006.github.io/GitHub-Collaboration-and-Deployment-/) • [Repository](https://github.com/Landyn006/GitHub-Collaboration-and-Deployment-) • [Issues](https://github.com/Landyn006/GitHub-Collaboration-and-Deployment-/issues)

</div>
