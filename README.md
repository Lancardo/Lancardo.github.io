# Academic Homepage

This repository contains a privacy-conscious academic homepage for Ruibo Lan. It is designed as a plain static site so it can be deployed directly with GitHub Pages.

## Included content

- Public research profile and selected background
- Representative publications with DOI links
- A public profile photo from GitHub
- GitHub Pages workflow for automated deployment

## Privacy choices

- Private application materials are not published
- No personal code numbers or direct private contact details are exposed
- Research summary is public-facing and concise
- The source folder with raw personal materials is ignored by Git and should remain local only

## Local preview

Run a simple static server from the repository root:

```powershell
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages deployment

1. Push this repository to a public GitHub repository.
2. In the repository settings, open **Pages**.
3. Set the build source to **GitHub Actions**.
4. Push to `main` again if needed. The included workflow will publish the site.

The site will then be available at:

- `https://<your-github-username>.github.io/<repository-name>/`
- Or `https://<your-github-username>.github.io/` if you publish from a repository named `<your-github-username>.github.io`
