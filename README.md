# Kenneth Johnson Portfolio

Static personal portfolio site for GitHub Pages.

Live site: [kennethjohnsontech.github.io](https://kennethjohnsontech.github.io/)

## Structure

- `index.html` - home page
- `work.html` - selected work index
- `work/` - project detail pages
- `writing.html` - writing index
- `styles.css` - shared layout, typography, and responsive styling
- `signature.png` - signature image used on the home page

## Local Preview

Run a static server from the repo root:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080/
```

## Deployment

This repository is configured as a GitHub Pages user site:

```text
KennethJohnsonTech/kennethjohnsontech.github.io
```

GitHub Pages publishes from the `main` branch at the repository root. There is no build step.
