# Qingyao Li Academic Homepage

This is a static academic personal homepage prepared for GitHub Pages.

## Structure

- `index.html`: the homepage content.
- `assets/css/styles.css`: responsive styling.
- `assets/img/profile.png`: homepage profile portrait.
- `assets/papers/`: local paper PDFs used by the publication list.
- `assets/cv/QingyaoLi_CV_English.pdf`: downloadable CV.
- `qa-*.png`: local QA screenshots, ignored by Git.

## Local Preview

Open `index.html` directly in a browser, or run a tiny static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

For a personal root site:

1. Create a GitHub repository named `<your-github-username>.github.io`.
2. Put all files from this folder at the repository root.
3. Commit and push to the default branch.
4. In GitHub, open the repository's `Settings` > `Pages`.
5. Choose `Deploy from a branch`, select the default branch, and set the folder to `/ (root)`.
6. Your site should appear at `https://<your-github-username>.github.io`.

For a project site, keep the repository name arbitrary and publish from the repository root or a `/docs` folder. The URL will usually be `https://<your-github-username>.github.io/<repository-name>/`.

## Notes Before Publishing

- GitHub Pages sites are public. Avoid committing passports, ID cards, signatures, private drafts, or files that should not be indexed.
- Update placeholder profile links such as Google Scholar, GitHub, ORCID, or homepage-specific analytics only after you decide what to expose publicly.
- If you add folders beginning with underscores, keep `.nojekyll` in the repository root so GitHub Pages serves the static files directly.

References:

- GitHub Pages overview: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages
- Publishing source settings: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
