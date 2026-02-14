# GitHub Pages Setup Instructions

This repository is now configured to work with GitHub Pages. To enable it:

## Steps to Enable GitHub Pages:

1. Go to your repository on GitHub: https://github.com/diptesh-bose/cv
2. Click on **Settings** (top menu)
3. In the left sidebar, click on **Pages** (under "Code and automation")
4. Under **Source**, select:
   - Source: **Deploy from a branch**
   - Branch: Select **main** (or the branch you want to deploy)
   - Folder: Select **/ (root)**
5. Click **Save**
6. Wait a few minutes for GitHub to build and deploy your site
7. Your CV will be available at: `https://diptesh-bose.github.io/cv/`

## What's Been Set Up:

- `index.md` - Your CV content in Markdown format
- `_config.yml` - Jekyll configuration with the Minima theme
- The content from `README.md` has been converted to a web-friendly format

## Customization:

You can customize the appearance by:
- Changing the theme in `_config.yml` (see available themes at https://pages.github.com/themes/)
- Adding custom CSS in a `assets/css/style.scss` file
- Modifying the layout and content in `index.md`

## Note:

The original `README.md` has been preserved and can still be viewed on the repository page.
