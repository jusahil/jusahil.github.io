# Sahil Imtiyaz — Quarto Academic Website

This is a ready-to-upload Quarto academic website project.

## Files included

- `_quarto.yml` — main Quarto website configuration
- `index.qmd` — homepage
- `research.qmd` — research overview
- `publications.qmd` — publications and manuscripts
- `projects.qmd` — projects
- `talks.qmd` — talks and seminars
- `cv.qmd` — CV page
- `contact.qmd` — contact and profile links
- `styles.css` — custom academic styling
- `.github/workflows/publish.yml` — GitHub Actions workflow for automatic publishing

## What you must edit first

Search for these placeholders and replace them:

- `YOUR-GITHUB-USERNAME`
- `YOUR-SCHOLAR-ID`
- `YOUR-ORCID-ID`
- `YOUR-LINKEDIN-ID`
- `YOUR-PROFILE`
- publication PDF / DOI / preprint links currently written as `#`

Also place your CV as `cv.pdf` in the root folder if you want the CV download button to work.

## How to publish on GitHub Pages

1. Create a GitHub repository named exactly:

   `YOUR-GITHUB-USERNAME.github.io`

2. Upload all files from this folder into that repository.

3. Go to repository **Settings → Pages**.

4. Under **Build and deployment**, choose **GitHub Actions**.

5. Commit or push the files. The workflow in `.github/workflows/publish.yml` will build and publish the site.

Your site should appear at:

`https://YOUR-GITHUB-USERNAME.github.io`

## Local preview, optional

If Quarto is installed on your computer, run:

```bash
quarto preview
```

To render locally:

```bash
quarto render
```
