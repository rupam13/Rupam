# Resume Website (GitHub Pages)

This folder contains a one-page resume website.

## 1) Customize

Edit `index.html` and update:
- Name, title, location, email
- LinkedIn and GitHub links
- Experience, projects, skills, education
- Footer date

Optional:
- Place your PDF as `resume.pdf` in this folder so the "Download PDF Resume" link works.

## 2) Create GitHub repository

Create a new public repository:

- Recommended: `yourusername.github.io` (for root GitHub Pages URL)

## 3) Push this code

Run these commands inside this folder:

```bash
git init
git add .
git commit -m "Add resume website"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

## 4) Open your website

If repo name is `yourusername.github.io`:

- `https://yourusername.github.io`

If repo name is different (for example `resume-site`), enable Pages in:

- GitHub repo -> Settings -> Pages
- Source: `Deploy from a branch`
- Branch: `main` and folder `/ (root)`

Then your URL will be:

- `https://yourusername.github.io/repo-name`
