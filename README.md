# Patrícia Szabó — Professional Portfolio

A fast, accessible, recruiter-focused portfolio presenting Patrícia Szabó’s work across research engineering, XR, digital health, HCI, and software engineering.

## Run locally

No build step or dependencies are required. From this directory:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. Opening `index.html` directly also works, but a local server is better for testing metadata and downloads.

## Deploy

The site is suitable for GitHub Pages, Cloudflare Pages, Netlify, or any static host. Publish the repository root. For GitHub Pages, choose **Deploy from a branch**, select the main branch and `/ (root)`, then configure the custom domain `patriciaszabo.dev` if that domain is confirmed.

## Update content

- Project, publication, and experience entries are data-driven in `script.js`.
- Biography, expertise, education, and international activities are in `index.html`.
- Visual design and responsive/print behavior are in `styles.css`.
- Replace `PATRICIA_SZABO_CV.pdf` when updating the downloadable CV.
- Replace `Patricia_Szabo_List_Of_Publications.pdf` when updating the full publication record.

## Accessibility and performance

The page uses semantic sections, a skip link, keyboard-friendly navigation, visible link treatment, responsive layouts, reduced-motion support, and print styles. JavaScript is limited to rendering structured content, the mobile menu, and the footer year.

## Content assumptions and confirmations needed

All professional claims come from the supplied CVs, publication lists, or recommendation letters. Before launch, confirm:

1. Whether `patriciaszabo.dev` is the production domain. Canonical, Open Graph, structured data, sitemap, and robots metadata currently use it based on the supplied professional email.
2. The preferred current formal title. One CV says “Assistant Professor”; another says “Researcher & Lecturer.” The site currently uses the evidence-safe positioning “Research Engineer” and lists “Researcher & Lecturer” in the timeline.
3. Public URLs for LinkedIn, Google Scholar, and GitHub. The PDFs display LinkedIn and Scholar labels, but their actual targets were not preserved during text extraction; no GitHub URL was supplied. They are intentionally omitted rather than guessed.
4. Whether Python should remain in the skills list. It appears in the latest one-page CV but not in the longer CV.
5. Preferred location/mobility wording for Germany and Europe.
6. Exact supervised-thesis count, if a verified number should replace “BSc and MSc theses.”
7. Project screenshots, prototype imagery, repository links, collaborator lists, and precise project dates for richer case studies.

## Privacy decisions

The public site intentionally excludes date and place of birth, phone number, personal Gmail address, postal addresses, and referees’ direct contact details. It uses the professional address `hello@patriciaszabo.dev` from the latest CV.
