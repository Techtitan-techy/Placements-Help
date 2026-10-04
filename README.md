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
- `gate2026.html`: The interactive GATE CS 2026 study guide.
- `robots.txt` and `sitemap.xml`: Search crawler directives and the public page sitemap.
- `vercel.json`: Vercel configuration for clean URLs.
- `.gitignore`: Files to exclude from version control.

## Search visibility

The pages include descriptive metadata, canonical URLs, Open Graph tags, a `robots.txt`
file, and a sitemap. The sitemap currently uses the default deployment URL
`https://placements-help.vercel.app`; update that host in `index.html`, `gate2026.html`,
`robots.txt`, and `sitemap.xml` if a custom domain is connected. Submit the sitemap URL
in Google Search Console after deployment. Search rankings and trending placement
cannot be guaranteed by code alone.
