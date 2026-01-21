# Professional Resume Website

A clean, responsive, and SEO-friendly personal portfolio website template. Built with HTML5, CSS3, and minimal JavaScript.

## 🚀 Quick Start

1.  **Open Locally**: Double-click `index.html` to view the site in your browser.
2.  **Edit Content**: Open `index.html` in a code editor (like VS Code).

## 📝 How to Update Content

The website is pre-filled with placeholder content. Follow these steps to make it yours:

1.  **Personal Info**: Search for `<!-- REPLACE:` comments in `index.html`.
2.  **Resume Download**:
    -   Save your actual resume as a PDF.
    -   Name it `resume.pdf`.
    -   Place it in the root folder (same folder as `index.html`).
3.  **Images**:
    -   Add your profile photo to an `assets/images` folder (create it if missing).
    -   Update the `<img>` src in the About section (if you add one).

## 🌍 Deployment (GitHub Pages)

Hosting this site for free on GitHub is easy:

1.  **Push to GitHub**:
    -   Initialize a git repo: `git init`
    -   Add files: `git add .`
    -   Commit: `git commit -m "Initial commit"`
    -   Create a repository on GitHub.
    -   Push your code: `git push -u origin main`
2.  **Enable Pages**:
    -   Go to your repository **Settings**.
    -   Click **Pages** in the left sidebar.
    -   Under **Build and deployment**, select **GitHub Actions** as the source.
    -   The workflow will automatically pick up the file we created.
    -   Your site will be live at `https://yourusername.github.io/repo-name/`.

## 🎨 Customization

-   **Colors**: Edit `css/styles.css` and change the variables at the top (`:root`).
    ```css
    :root {
        --primary-color: #2563eb; /* Change this hex code */
    }
    ```
-   **Fonts**: The site uses 'Inter' from Google Fonts. tailored in `<head>` of `index.html`.
