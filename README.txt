README — HTML-Only Portfolio
============================

Contents
--------
- index.html
- contact.html
- assets/profile.jpg

Notes for the W3C Validator
---------------------------
- The pages are intentionally HTML-only: no CSS or JavaScript included.
- If you see warnings (not errors) about using headings in order: this project uses a single <h1> per page,
  followed by <h2> for major sections and <h3> for project titles to preserve hierarchy.
- If you get warnings about link text like "Live Demo" or "Source Code", they are paired with surrounding context titles to keep meaning clear.

How to Use
----------
1) Replace the placeholder links (#) and social URLs with your real ones.
2) Replace assets/profile.jpg with your real photo.
   - Keep the filename the same or update the <img> src attributes accordingly.
3) Validate both pages at https://validator.w3.org/ (no errors expected).

Git Commands
------------
    git init
    git add .
    git commit -m "Initial commit: HTML-only portfolio"
    git remote add origin https://github.com/<your-username>/html-portfolio.git
    git branch -M main
    git push -u origin main

Enable GitHub Pages
-------------------
- On GitHub, go to Settings → Pages.
- Source: Deploy from a branch → Branch: main (/root) → Save.
- Your site will be available at: https://<your-username>.github.io/html-portfolio/

Accessibility Checklist
-----------------------
- <html lang="en"> present
- One <h1> per page
- Meaningful alt text for images
- Logical heading order (h1 → h2 → h3)
- Descriptive link text with context
- <meta charset> and <meta name="viewport"> present
