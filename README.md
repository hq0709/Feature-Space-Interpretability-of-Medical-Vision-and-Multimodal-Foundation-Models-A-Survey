# fm-survey — Overleaf mirror (v7.29)

Compile-only export of the survey for Overleaf's GitHub import. Main document: `main.tex`
(elsarticle, pdflatex + bibtex). Supplementary tables: `supplement/supplement_tables.tex`.

Everything here is generated from the full repository (https://github.com/hq0709/fm-survey) by
`tools/export_overleaf.sh` after `tools/build.sh`; the count macros (`sections/*_counts.tex`) and the
generated tables (`tables/tab_*.tex`) are build outputs, so edit the full repository's sources and
re-export rather than editing them here. Author artwork goes in `figures/` (same file names).
