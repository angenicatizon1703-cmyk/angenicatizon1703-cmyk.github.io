# Angenica Tizon — IT Portfolio

A responsive, plain HTML/CSS/JavaScript portfolio with no build dependencies. Contains a professional hero, work experience, project case studies, skills, degree and credential gallery (15 uploaded images/PDFs), theme toggle, filtering, search, and contact shortcuts.

## Run locally

For best results, start a small local server inside this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser. You can also open `index.html` directly, though local hosting is preferable for testing.

## Deploy for free

Upload the entire folder contents to GitHub Pages, Netlify, or Vercel as a static site. Keep the `assets/` folder beside `index.html`.

## Before publishing

1. Review the personal contact information, resume, and certificates. They become public if the website is public.
2. Replace the project illustrations with screenshots of your actual work; add GitHub repository and demo URLs to case studies as available.
3. Add any portfolio project details, metrics, and testimonials you can substantiate. Existing project descriptions are based on your submitted resume.
4. The certificates include *CCNA: Switching, Routing, and Wireless Essentials course completion*. This site intentionally does **not** claim a full CCNA exam certification.
5. The degree image is dated August 9, 2026; the resume uses a different graduation date. This site displays only 2026 to avoid a potentially confusing conflict.
6. Site does not collect visitor data or send messages. The email button opens the visitor's email app. A contact form would need a backend or third-party service.
7. The photo is extracted from your submitted résumé.

## Edit content

- `index.html`: site layout, social links, contact, headline.
- `styles.css`: visual theme and layout.
- `script.js`: the `skills`, `experiences`, `projects`, and `certs` data arrays and interactions.
- `assets/docs`: resume and profile PDFs.
- `assets/certificates`: original certs and previews.

Built with accessible semantic HTML, responsive layout, reduced-motion support, and lazy-loaded certificate previews.
