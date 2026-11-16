# Abhilasha J. Saroj — academic website

A simple, responsive, **zero-build** academic website, prepared for GitHub Pages. It includes a research-oriented homepage, research initiatives, **all 36 publication records** in the supplied CV (8 journal, 24 conference, 4 under review/preprints), teaching and mentorship, education, honors, leadership, professional profiles, and selected media links. Includes a downloadable copy of the supplied CV.

## Publish it on GitHub Pages (no coding required)

The verified GitHub account confirmed through your connected GitHub is **[@abhilashasaroj17](https://github.com/abhilashasaroj)**.

1. Log into GitHub as `abhilashasaroj17`.
2. Go to [Create a new repository](https://github.com/new).
3. Name the repository **`abhilashasaroj17.github.io`** (exact spelling). Choose **Public** and click **Create repository**. Do not add a starter README because this package already includes one.
4. Unzip the package from ChatGPT. In the new GitHub repository, choose **Add file → Upload files** and drag in the **contents of the `abhilashasaroj17.github.io` folder**, not the containing folder itself. `index.html` must be at the repository root alongside this README. Commit the files to the `main` branch.
5. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select **`main`**, folder **`/(root)`**, then **Save**.
6. After GitHub completes the Pages deployment, your site will be available at **https://abhilashasaroj17.github.io/**. This address is the *intended* site URL, not a claim that the site is already live.

If Pages shows a blank site or a 404, check that `index.html` is at the repository root, the `main` branch was selected, and the Pages build has completed in the **Actions** tab.

Official guide: https://docs.github.com/en/pages/quickstart

### Alternative: publish using Git on your computer

```bash
# Run these commands INSIDE the unzipped abhilashasaroj17.github.io folder.
git init
git branch -M main
git add .
git commit -m "Launch academic website"
git remote add origin https://github.com/abhilashasaroj17/abhilashasaroj17.github.io.git
git push -u origin main
```

Create the empty repository first and authenticate via Git Credential Manager / GitHub CLI as GitHub requires; a password is not accepted for HTTPS Git operations.

## Edit the site

- **Words, sections, and links:** `index.html`.
- **Colors, typography and mobile styles:** `assets/style.css`.
- **Navigation menu, publication category filters:** `assets/site.js`.
- **Publication list:** Current publication cards are pre-rendered in `index.html` for accessibility and search indexing. The same entries are also supplied as reference data in `assets/publications.json` for convenient updates; **editing JSON alone does not change the webpage**. Update the corresponding card in `index.html`, or regenerate it from your own template.
- **Updated CV:** Replace `Abhilasha_Saroj_CV.pdf` with your latest CV, keeping this filename or updating the linked filename in `index.html`.
- **Add a headshot:** No portrait is included because one was not provided. You may replace the decorative network illustration in the hero with your own photo later.

The page works without external fonts, packages, trackers, or paid hosting. Open `index.html` in a web browser to preview it locally before publishing.

## What was verified, and what to review

The ORNL staff profile, Google Scholar link, LinkedIn profile, ORCID, GitHub account, IEEE chapter listing and Georgia Tech media URLs were checked against public pages and/or links embedded in the supplied CV. Some historic news links can change after website redesigns. Your CV uses `Research Scientist` and the live ORNL profile uses `Advanced Mobility R&D Staff`; the website uses the CV's research scientist description and links to the official profile for the current title.

**Personal-review checklist:**
- Review your research-vision prose, which is a concise synthesis based on the CV, and adjust for each faculty application.
- Check forthcoming WACV 2027 and ACM SIGSPATIAL 2026 publication statuses periodically. They are intentionally marked “proceedings forthcoming,” not published.
- Check that the title `IEEE Senior Member` is current and appropriate for public display, and update other awards as needed.
- Consider adding a photo and PDF teaching/research statements as you prepare specific applications.
- Review that you are happy publishing the supplied CV's contact details. The website intentionally publishes your ORNL email but **not your phone number**.

## File structure

```text
abhilashasaroj17.github.io/
├── index.html
├── Abhilasha_Saroj_CV.pdf
├── README.md
├── .nojekyll
└── assets/
    ├── favicon.svg
    ├── style.css
    ├── site.js
    └── publications.json
```

*This is a personal website and does not imply endorsement by ORNL, Georgia Tech, IEEE, or DOE.*