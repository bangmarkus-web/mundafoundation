# Munda Foundation — GitHub Pages build

## Structure
- index.html (Norwegian)
- index-en.html (English)
- success.html (Norwegian thank-you)
- success-en.html (English thank-you)
- images/
- styles/
- data/
- admin/ (placeholder only)

## Paths
All asset paths are relative (./styles, ./images, ./data) for GitHub Pages.

## Forms (Formspree)
The contact forms point to a placeholder endpoint:
`https://formspree.io/f/REPLACE_ME`

Create a free Formspree form and replace with your actual endpoint in both:
- index.html (uses _next ./success.html)
- index-en.html (uses _next ./success-en.html)

## GitHub Pages settings
Settings → Pages:
- Source: Deploy from a branch
- Branch: main
- Folder: / (root)

Your site URL will be listed at the top of the Pages settings.
