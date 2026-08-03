# Overleaf resumes — use these for PDF layout

Your original PDF used **Bitstream Charter**, simple one-column layout, ~9pt body, ~16pt name.  
These `.tex` files match that layout. Content is Master Truth (not the old inflated Adobe claims).

## Files

| File | Use |
|---|---|
| `resume-backend.tex` | Default apply PDF |
| `resume-fullstack.tex` | FE-heavy JDs only |

## How to use in Overleaf

1. New Overleaf project (Blank)
2. Replace `main.tex` with the contents of `resume-backend.tex` (or fullstack)
3. Menu → Compiler: **pdfLaTeX**
4. Download PDF → `Pranjali-Sankpal-Resume-Backend.pdf`

## Local compile

```bash
cd career-job-os/03-resume/overleaf
pdflatex resume-backend.tex
pdflatex resume-fullstack.tex
```

Previews also in `../exports/` after compile.

## Layout rules (do not break)

- Font: Charter
- Single column, no sidebar, no icons, no color chips
- Section order: Summary → Technical Skills → Experience → Projects → Open Source → Education → Certifications
- Skills as labelled lines (`Languages: ...`)
- Job title left, dates right
- Keep one page
- Body ~9pt (same as your original; Charter stays readable)

## Content source

Edit facts only via Master Truth + these tex files. Markdown masters stay for agents; **PDF = Overleaf tex**.
