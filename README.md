# Minimal Project-Notes Portfolio

This is a clean GitHub Pages portfolio focused on project writing, not full CV details.

## Structure

- `index.html` - profile summary + project cards
- `styles.css` - minimal UI style
- `script.js` - mobile nav + reveal animation
- `posts/*.html` - blog-style project writeups
- `posts/post.css` - post page style
- `resume.html` - temporary resume placeholder page
- `.nojekyll`

## Customize

1. Edit `index.html`:
   - Name, role, location
   - GitHub/LinkedIn links
   - Email and resume link
2. Edit each file in `posts/` with your real project details.
3. If you have a PDF resume, upload it in root and change `resume.html` links to `resume.pdf`.

## Deploy

For user site deployment:

1. Push all files to `username.github.io` repository root.
2. In GitHub Pages settings, use:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/(root)`
3. Open `https://username.github.io`.
