# Items Needing Your Input
## torreymortenson.github.io Setup — Disposition List

This file lists information that was missing, ambiguous, or that you should review before publishing the site. Work through this list and update the relevant files.

---

### 1. Profile Photo
- **File needed:** `images/profile.png` (or `bio-photo.jpg`)
- **Action:** Replace the placeholder profile image with your own headshot. The `_config.yml` currently references `profile.png`. Crop to roughly square (400×400px or larger) for best results.

---

### 2. Academic / Professional Profile Links
These fields in `_config.yml` are left blank — add URLs when ready:

- `googlescholar` — Your Google Scholar profile URL (e.g., `https://scholar.google.com/citations?user=YOURID`)
- `orcid` — Your ORCID URL (e.g., `https://orcid.org/0000-0000-0000-0000`)
- `linkedin` — Your LinkedIn username
- `researchgate` — Your ResearchGate profile URL (if you use it)

---

### 3. CV PDF
- **Action:** Upload your current CV as `files/Mortenson_CV.pdf`
- The CV page links to `/files/Mortenson_CV.pdf`. You can use the attached `Mortenson_CV_04-2026.pdf` — just rename it and drop it in the `files/` directory.

---

### 4. Publication DOIs / Paper URLs
The following publications do not have confirmed public URLs. Add `paperurl:` values in the respective `_publications/` files when you locate them:

- All PSAM 2026 papers (in press — add when published)
- All NPIC-HMIT 2025 and PSA 2025 papers — check conference proceedings
- Pacific Basin Nuclear Conference 2024
- PSA 2023 paper
- PSAM16 (2022) papers
- AHFE 2021 papers (Springer — check for DOI)
- NPIC&HMIT 2021 papers
- HFES 2020 and 2021 papers (SAGE — check for DOI)
- INL technical reports — most are publicly available at https://www.osti.gov — search by report number

---

### 5. Google Analytics (Optional)
- If you want site traffic analytics, add a Google Analytics 4 tracking ID in `_config.yml` under `analytics.google.tracking_id`.

---

### 6. Talks / Presentations
The `_talks/` directory still contains template placeholder files. You should:
- Delete `_talks/2012-03-01-talk-1.md`, `_talks/2013-03-01-tutorial-1.md`, etc.
- Add real talks or leave the page sparse for now — the template will show "no talks found" gracefully if all placeholders are removed.
- Good candidates to add: NRC training sessions you delivered, conference presentations (especially invited/keynote), any public lectures.

---

### 7. Portfolio
- The `_portfolio/` directory has template placeholders. Options:
  - Leave as-is (shows sample content)
  - Replace with real project entries (e.g., Civix Design project spotlights, INL research tools, ERGON method, visualization work)
  - Delete placeholder files if you want the portfolio to be empty for now

---

### 8. Blog Posts
- The `_posts/` directory has placeholder blog posts from 2012–2015. Delete these before publishing, or replace with real posts.
- Consider cross-posting from *Where Sidewalks End* if appropriate, or using this space for professional commentary.

---

### 9. Sidebar Bio
- The current sidebar bio in `_config.yml` reads: *"Human Factors Research Scientist at Idaho National Laboratory. Adjunct Professor at University of Idaho. Founder of Civix Design."*
- Review and adjust tone/length to taste. Max ~2–3 sentences for clean display.

---

### 10. INL Publication Restrictions
- Some INL technical reports are limited release (`[Limited Release]` noted in your CV). Verify which can be publicly linked before adding `paperurl` values to those files.
- INL/LTD-20-58848 (*Scalability of a Risk-Informed Predictive Maintenance Strategy*) was flagged as Limited Release in your CV — this one has **no public paperurl** in the site files as a precaution. Confirm before adding.

---

### 11. Pronoun Field
- `pronouns:` in `_config.yml` is blank. Add if desired (e.g., `he/him`).

---

### 12. Bluesky / Social
- `bluesky:` in `_config.yml` is blank. Add your handle if you have one.
- Same for LinkedIn username (separate from the full URL under `linkedin:`).

---

### 13. Co-author Profile Links (Optional)
- Publication pages currently just list citation text. If you want to add hyperlinks to co-author profiles (e.g., Randy Boring, Tara Ulrich), add them manually to the body of the relevant `_publications/*.md` files.

---

*Generated automatically during site setup. Delete or archive this file before or after publishing.*
