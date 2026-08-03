# Layout spec — match original PDF (reference only)

Source reference: user-uploaded `Pranjali_Sankpal_Resume_7a33.pdf` (layout only; content from Master Truth v2).

## Measured from original

| Element | Original |
|---|---|
| Page | Letter / A4 one page |
| Body font | Bitstream Charter (CharterBT-Roman) |
| Body size | ~9 pt |
| Name | ~16 pt Bold |
| Section headers | ~11–12 pt Bold |
| Contact / title line | ~10 pt |
| Structure | Single column, no sidebar, no icons, no color blocks |
| Skills | Labelled lines (`Languages: ...`) not skill chips |
| Jobs | Title + company + location left; dates right |
| Bullets | Short 1–2 lines; standard round bullets |
| Sections | Summary → Technical Skills → Experience → Projects → Open Source → Education → Certifications |

## What felt wrong in markdown-only v2

- Story bullets became long paragraphs (harder to scan than the original)
- No fixed Overleaf template → font/size drifted smaller when crammed
- Extra header lines (relocation) ate space

## Target for Overleaf v2.1 layout

| Element | Choice | Why |
|---|---|---|
| Font | Charter (`\usepackage{charter}`) | Same family as original |
| Body | **9 pt** | Match original measured size (readable with Charter) |
| Name | ~16 pt bold | Match original |
| Section headers | ~11 pt bold + rule | Match original |
| Margins | ~0.5 in | Simple, one page |
| Bullets | Short 1-2 lines | Scannable like original |
| Content | Master Truth only | Layout reference is not permission to copy old inflated claims |

## Files

- `overleaf/resume-backend.tex` / `resume-fullstack.tex`
- `exports/Pranjali-Sankpal-Resume-Backend.pdf` (compiled preview)
- `MASTER-RESUME-*-v2.1.md` (markdown mirror)
