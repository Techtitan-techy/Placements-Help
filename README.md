# Placement Sheet 2026 - Deployment

This project is configured for easy deployment to **Vercel**.

## How to Deploy

### Option 1: Using GitHub (Recommended)
1.  Initialize a Git repository in this folder:
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    ```
2.  Create a new repository on GitHub and push your code there.
3.  Go to [vercel.com](https://vercel.com) and click **"Add New"** > **"Project"**.
4.  Import your GitHub repository.
5.  Click **"Deploy"**.

### Option 2: Using Vercel CLI
1.  Install Vercel CLI: `npm i -g vercel`
2.  Run the following command in this directory:
    ```bash
    vercel
    ```
3.  Follow the prompts to deploy.

## Project Structure
- `index.html`: The main placement sheet.
- `vercel.json`: Vercel configuration for clean URLs.
- `.gitignore`: Files to exclude from version control.
