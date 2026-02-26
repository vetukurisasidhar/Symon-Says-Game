# Simple Web Project

This repository contains a small web project with the following files:

- `index.html` &ndash; basic HTML page
- `app.js` &ndash; JavaScript logic
- `style.css` &ndash; styles for the page
- image assets (`*.png`, `*.jpeg`)

## Getting Started

1. Clone or download the repository to your machine.
2. Open `index.html` in a browser or serve the folder using a simple HTTP server (e.g. `npx http-server`).

## Pushing to GitHub

To add this project to GitHub, install Git, then run the following from the project root:

```bash
# initialize a new local repository
cd /path/to/JS
git init

# add remote (change URL to your repo)
git remote add origin https://github.com/vetukurisasidhar/first-one.git

# stage and commit files
git add .
git commit -m "Initial commit"

# push master/main branch
git push -u origin main
```

If you already have a repository on GitHub you can update the `origin` URL accordingly.

## .gitignore

Images, OS files and node modules (if applicable) can be ignored:

```
# ignore image assets if they are large
*.png
*.jpeg

# Mac/Windows system files
.DS_Store
Thumbs.db
```
