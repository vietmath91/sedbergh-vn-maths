# Sedbergh VN Maths

This repository builds the **Sedbergh VN Maths** site with **GitHub Pages + Jekyll**.

The site provides:
- Cambridge **IGCSE** practice worksheets (Number, Algebra, Geometry, Statistics & Probability).
- Cambridge **AS** (Pure 1 and Statistics 1).
- Cambridge **A2** (Pure 3 and Statistics 2).
- **UKMT training** sets and competition practice.
- **Reflections** on teaching and leadership.
- General **maths competition** resources.

## Structure

- `_config.yml` → Jekyll configuration  
- `_includes/head.html` → adds MathJax support  
- `index.md` → homepage  
- `igcse/`, `as/`, `a2/` → section landing pages  
- `_worksheets/` → all worksheet pages (auto-published)  
- `_ukmt/` → UKMT training materials  
- `_competitions/` → competition prep notes  
- `_reflections/` → teaching reflections  

## Editing content

1. Add new Markdown files into the relevant collection folder (e.g. `_worksheets`).
2. Use LaTeX inside `\( ... \)` or `$$ ... $$` for maths — MathJax renders it.
3. Commit to the `main` branch. GitHub Actions will rebuild and deploy the site.

## Live site

The live site is available at:

👉 [https://vietmath91.github.io/sedbergh-vn-maths/](https://vietmath91.github.io/sedbergh-vn-maths/)
