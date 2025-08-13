
# Cybersecurity Portfolio (Corporate Theme)

A clean, professional portfolio you can deploy on **GitHub Pages**.

## Quick Start
1. Create a new GitHub repo (e.g., `cybersecurity-portfolio`).
2. Upload all files from this folder to the repo root.
3. Go to **Settings → Pages**:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (root)
4. Wait for Pages to build, then visit the site URL shown in the Pages section.

## Personalize
- Replace `YOUR NAME`, `YOUR TITLE`, and contact info in `.html` files.
- Add your **resume** as `assets/img/resume.pdf`.
- Duplicate a project page (e.g., `project-incident-response.html`) for your own projects.
- Update `sitemap.xml` and `robots.txt` with your GitHub username and repo name for best SEO.
- Optional: add a custom domain via **Settings → Pages** (create a `CNAME` file).

## Structure
```
/
├─ index.html
├─ about.html
├─ projects.html
├─ project-incident-response.html
├─ project-security-audit.html
├─ certifications.html
├─ resume.html
├─ contact.html
├─ assets/
│  ├─ css/main.css
│  ├─ js/main.js
│  └─ img/ (place images & resume.pdf here)
├─ robots.txt
├─ sitemap.xml
├─ LICENSE
└─ README.md
```

## Notes
- Keep sensitive details out of screenshots—redact names, emails, IPs, etc.
- This site is static HTML/CSS; no build step required.
- Works great as a companion to a private Google Drive folder with raw artifacts.
