# Handbook App Deployment Guide

This folder contains the standalone `index.html` for the Handbook App (異形管便覧検索).

## How to Deploy to GitHub Pages

1.  **Initialize Git**:
    Open a terminal in this `handbook-deploy` folder:
    ```bash
    git init
    git add .
    git commit -m "Initial commit of Handbook App"
    ```

2.  **Create a Repository on GitHub**:
    - Go to [GitHub.com](https://github.com) and create a new repository (e.g., `handbook-app`).
    - Do **not** initialize with README, .gitignore, or license (keep it empty).

3.  **Push to GitHub**:
    Run the commands shown on the GitHub repository page (replace `YOUR_USERNAME` and `REPO_NAME`):
    ```bash
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
    git push -u origin main
    ```

4.  **Enable GitHub Pages**:
    - Go to the repository **Settings** tab.
    - Click **Pages** in the left sidebar.
    - Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/(root)`.
    - Click **Save**.

Your app will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/` shortly!
