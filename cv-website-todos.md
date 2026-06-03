# CV & website update todos

Track missing entries discussed in Mar 2026. Check off items as completed.

---

## HCIC invited talks (CV)

- [ ] **Gather talk history** — Search email (Gmail: `HCIC OR "Human-Computer Interaction Consortium"`) and/or calendar for invitations, confirmations, and programs. Record for each year: date/year, exact title, and role (invited talk vs. keynote, etc.).
- [ ] **Confirm 2026 talk** — Verify spelling and title for *Design for Disobedience* (or official program title) at HCIC 2026.
- [ ] **Add entries to `cv.tex`** — Under `\section*{Symposium Talks}` (or `\section*{Invited Keynote Talks}` if that matches how you classify HCIC), add one `\years{YYYY}...` line per talk with title and `\hfill HCIC` (or `Human-Computer Interaction Consortium` for consistency with the 2024 organizing entry).
- [ ] **Mirror in `cv2page.tex`** — If the two-page CV is still in use, add the same HCIC talk lines there (section is `\section*{Conference Symposium Talks}`).
- [ ] **Rebuild PDF** — Recompile `cv.tex` and update `Academic_CV.pdf` if that file is checked into the repo / deployed from here.
- [ ] **Quick audit** — Ensure HCIC *organizing* (2024 “History and Future of HCI”) stays under Service → Small Conference and Workshop Organizing Committees and is not confused with talk entries.

---

## CV title audit: Trustworthy AI for Code

- [ ] **Verify full roundtable title** — Confirm `\section*{Invited Keynote Talks}` lists **Trustworthy AI for Code Industry Roundtable** (2026, IBM NYC/Columbia), not the shortened **AI for Code**. As of last check, `cv.tex` has the full title under Invited Keynote Talks; **AI for Code** (2024, Google DeepMind) is a separate entry under Invited Seminar Talks — make sure they stay distinct and the roundtable is not missing or mislabeled on either CV file or the PDF.

---

## Curiosity Desk appearance

- [ ] **Gather details** — Episode title, air/date (or taping date), role (guest, expert, etc.), and link (WGBH / YouTube / station page if available).
- [ ] **Add to `cv.tex`** — Pick section (likely `\section*{Selected press}` or `\section*{Selected Outreach}`; add a new subsection only if nothing fits). Use same `\years{}` / `\hfill` format as neighboring lines.
- [ ] **Mirror in `cv2page.tex`** — If applicable.
- [ ] **Rebuild PDF** — Recompile and refresh `Academic_CV.pdf` if maintained here.

---

## Personal / lab website

> Website source is **not** in this repo (lab site: `https://glassmanlab.seas.harvard.edu/`). Update wherever that site is built (separate repo, CMS, or static site).

- [ ] **Locate website source** — Find repo or editor for faculty page / news / media section.
- [ ] **Add Curiosity Desk** — List appearance with date, title, and link on an appropriate page (e.g. media, news, or talks/outreach).
- [ ] **Optional: add HCIC talks** — If the site lists invited talks, add the same HCIC history (and 2026 talk) for consistency with the CV.
- [ ] **Publish / deploy** — Push changes and confirm the live page.

---

## Done when

- [ ] CV lists all HCIC invited talks (including 2026) with correct titles and years.
- [ ] **Trustworthy AI for Code Industry Roundtable** appears with full title (not just “AI for Code”).
- [ ] CV lists Curiosity Desk appearance.
- [ ] Live website reflects Curiosity Desk (and HCIC talks if desired).
