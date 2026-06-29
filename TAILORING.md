# Resume Tailoring Checklist

**The problem this solves:** Most aerospace/manufacturing jobs run your resume through an
ATS (Workday, Taleo, iCIMS, SuccessFactors) that scores keyword overlap with the *specific*
job description before any human sees it. One static resume matches some postings well and
many poorly — the poorly-matched ones get auto-filtered. Spending 5 minutes mirroring each
posting's language is the single highest-leverage move for getting screening callbacks.

Master file for process/manufacturing roles: `resume-process-eng.html`
Keep the AI-forward version (`resume.html`) for hybrid / Industry-4.0 roles only.

---

## Per-application checklist (~5 min)

1. **Paste the job description into a scratch doc.** Highlight every:
   - Hard requirement (degree, years, clearance, location, specific spec numbers)
   - Repeated noun phrases (e.g. "anodize", "GD&T", "Cpk", "AS9100", "PPAP", "FAI")
   - The exact job title as written (e.g. "Manufacturing Engineer II", "Process Engineer III")

2. **Mirror the title language.** If the posting says "Manufacturing Engineer," make sure the
   word *Manufacturing* appears in your summary. ATS matches literal strings — "Process Engineer"
   does not auto-match "Manufacturing Engineer."

3. **Mirror the keywords using THEIR exact terms.** If they write "Cpk," don't leave it as
   "process capability" — write "process capability (Cpk)." If they write "corrective action
   (CAPA)," make sure CAPA appears. Only claim what's true; reword, don't invent.
   - Easy place to add terms without disturbing layout: the **Technical Skills** line and the
     **Core Competencies** blocks.

4. **Match years/requirements explicitly** when you meet them. If they want "5+ years in
   chemical processing," your 25+ already covers it — make sure "chemical processing" is a
   literal phrase on the page.

5. **Export a fresh PDF** (see below) and **name the file** for the role:
   `Hector-Garza-Process-Engineer-<Company>.pdf`. Never upload `resume-process-eng.html` as-is.

6. **Also paste plain text** if the application has a "paste resume" box — that path bypasses
   PDF parsing entirely and is the most ATS-safe of all.

---

## ATS hygiene (already handled in resume-process-eng.html)

- Single-column, no flexbox/table columns — text extracts in reading order.
- Standard section headers: Summary, Core Competencies, Certifications & Standards,
  Professional Experience, Technical Skills, Education.
- Real bullet lists, no icons, no text-in-images.
- Arial throughout, consistent 10pt (per Harvard OCS formatting guidance: common font,
  10–12pt, consistent), equal 0.5in margins, no text boxes / underlining / shading.

**Do not** add columns, text boxes, headers/footers, or graphics — they re-break ATS parsing.

---

## Exporting the PDF

Open `resume-process-eng.html` in Chrome → Print → "Save as PDF" → set margins to *Default*,
scale 100%, background graphics ON. The layout is print-tuned for US Letter.

After exporting, sanity-check parsing: open the PDF, Ctrl+A to select all, Ctrl+C, paste into
a plain text editor. If the text comes out in the right order and nothing is missing, the ATS
will read it correctly.

---

## Known constraints to be aware of

- **Degree is B.S. Chemistry, not "Engineering."** A few postings hard-filter on an engineering
  degree. Nothing to fix on the resume — but if a role rigidly requires "BS in Engineering,"
  it may auto-reject regardless. Prioritize postings that say "engineering or related technical
  degree" or that emphasize experience.
- **Location: Greensboro, NC.** Remote/relocation-flagged roles screen on this. If you'd relocate,
  add "open to relocation" to the summary for those specific postings.
