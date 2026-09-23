# Khashayar Pourtaheri's personal website

This is a small, dependency-free static site designed for GitHub Pages. It contains a home page, an about page, a research page, and the profile photo in the repository.

## Publish it

1. Create a new GitHub repository, preferably named `khashayar-pourtaheri.github.io` for a personal GitHub Pages address.
2. Upload these files and push them to the `main` branch.
3. In the repository, open **Settings → Pages** and set **Source** to **GitHub Actions**.
4. The included workflow will deploy the site whenever changes are pushed to `main`.

For a repository named `khashayar-pourtaheri.github.io`, the usual address is `https://khashayar-pourtaheri.github.io/`. For any other repository name, GitHub Pages uses `https://<github-username>.github.io/<repository-name>/`. The site's relative page links work in either location.

## Update content

- Edit `about.html` for the biography and contact details.
- Edit `research.html` to add papers and working projects.
- Replace the CV placeholder in `cv.html` with a link to a revised PDF in `assets/files/`. Do not add a CV until it has been checked for private contact details.
- Replace `assets/images/khashayar-pourtaheri.jpg` to update the portrait (keep the same filename).

No site generator or package installation is needed: edit the HTML and CSS files directly, then push changes to GitHub.
