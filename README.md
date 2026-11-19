# PolyU Beamer template

Personal version of the PolyU Beamer template, originally created by [wurahara](https://github.com/wurahara).

Overleaf: https://www.overleaf.com/project/6afa78d175d38443bdc62a2c/share#795d3b7c80f3e5077f961123a1677691b07e9051348dd662

Build with pdfLaTeX (`demo.tex`), **twice** for TikZ overlays and TOC.

## Layout helpers (`polyu_layout.sty`)

Brand tab, title page, footline numbers, `\studypair` / `\studypairsm` / `\studypairxy`, `\drawcard` / `\drawcards`, `\sessionsketch`, `\roadmaprows`, `\centerstate`, `\plaintable`, centered `\QApage`.

Optional preamble overrides: `\renewcommand{\titleheropath}{...}`, `\renewcommand{\titleheroheight}{0.55\paperheight}`.

## Overleaf upload

Zip / sync the whole repo root (keep folder structure):

| Path | Needed |
| :--- | :----- |
| `demo.tex` | Main compile target |
| `collegebeamer.sty` | Theme |
| `polyu_layout.sty` | Visual layer |
| `src/PolyU/` | Emblems / logos / backgrounds |
| `gallery/` | Filler images used by `demo.tex` |

Do **not** need: `.git/`, local `demo.pdf` (Overleaf rebuilds). Compile with **pdfLaTeX**.
