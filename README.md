# Personal Portfolio Website

This is a clean, modern, and professional developer portfolio built specifically using **HTML, CSS, and Vanilla JavaScript**. It focuses on elegant design, perfect typography, smooth animations, and solid performance.

## Project Structure
```text
portfolio/
 ├ index.html      # Main HTML file containing structure and content
 ├ style.css       # Styling, themes, responsive layout, animations
 ├ script.js       # Smooth scrolling, mobile menu, and reveal animations
 └ README.md       # Documentation (this file)
```

## How to Run Locally

You don't need any complex build tools (like Node.js, Webpack, etc.) to run this website.

1. **Directly via Browser**: 
   Simply double-click the `index.html` file to open it in your default web browser (Chrome, Firefox, Safari, Edge).

2. **Using VS Code Live Server** (Recommended):
   - Open this folder in Visual Studio Code.
   - Install the extension called **"Live Server"**.
   - Right-click on `index.html` and select **"Open with Live Server"**.
   - A local development server will start holding hot-reloading (changes reflect instantly).

## How to Add New Projects Later

To add a new project to your portfolio, you simply need to copy an existing "Project Card" block in `index.html` and edit its contents.

1. Open `index.html`.
2. Find the `<section id="projects">` block.
3. Inside `<div class="projects-grid">`, paste the following blueprint:

```html
<div class="project-card reveal">
    <div class="project-content">
        <div class="project-header">
            <div class="project-type">Project Category / Type</div>
            <div class="project-links">
                <a href="LINK_TO_GITHUB" target="_blank"><i class="fab fa-github"></i></a>
                <a href="LINK_TO_LIVE_PREVIEW" target="_blank"><i class="fas fa-external-link-alt"></i></a>
            </div>
        </div>
        <h3 class="project-title">Your New Project Title</h3>
        <div class="project-description">
            <p>A brief introductory overview of what the project does.</p>
            <ul>
                <li>Key feature 1</li>
                <li>Key feature 2</li>
            </ul>
        </div>
        <div class="project-tech-stack">
            <span>Tech 1</span>
            <span>Tech 2</span>
            <span>Tech 3</span>
        </div>
    </div>
</div>
```
4. Customize the text, links, and technologies as needed. The styles and hover effects will automatically apply!

## How to Deploy on GitHub Pages

Hosting this site on GitHub Pages is completely free and straightforward.

1. **Create a new Repository**:
   - Go to GitHub and create a new repository (e.g., `harsh-portfolio`).
   - Do NOT initialize it with a README, .gitignore, or license yet.

2. **Upload your code**:
   - Open your terminal and navigate to this `portfolio` directory.
   - Run the following commands:
     ```bash
     git init
     git add .
     git commit -m "Initial commit of portfolio"
     git branch -M main
     git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
     git push -u origin main
     ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **"Settings"** (the gear icon).
   - In the left sidebar, scroll down and click on **"Pages"**.
   - Under the **"Source"** dropdown, select **`main`** branch and click **"Save"**.
   - Wait a couple of minutes, refresh the page, and GitHub will provide you with a live link (e.g., `https://yourusername.github.io/harsh-portfolio/`).

---

**Tip:** Before deploying, remember to update the social links (GitHub, LinkedIn, Email) in the `<section id="contact">` within `index.html` with your actual URLs!
