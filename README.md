# PG Diploma Thesis Latex Template

This repository provides a LaTeX template for diploma theses at the Gdańsk University of Technology. The template is designed to comply with the guidelines specified in [Zarządzenie Rektora PG nr 45/2024](https://cdn.files.pg.edu.pl/main/DZJ/Jako%C5%9B%C4%87%20kszta%C5%82cenia/akty%20prawne/Zarz%C4%85dzenia/2024%202025/ZR%2045-2024%20w%20sprawie%20wprowadzenia%20wytycznych%20dla%20autor%C3%B3w%20prac%20dyplomowych.pdf).

## Requirements

This template requires a modern LaTeX engine for compilation. Supported engines:

- **LuaLaTeX** (recommended)
- **XeLaTeX** (not tested)

### Key Guidelines

- **Font**: Arial, 10 pt size.
- **Line Spacing**: 1.5 lines.
- **Margins**: Mirror layout (inner: 3.5 cm, outer: 2.5 cm, top/bottom: 2.5 cm).
- **Page Numbering**: Continuous, in the footer (not visible on the title page).
- **Figure and Table Captions**:
  - Above tables.
  - Below figures.
- **Bibliography**: Ensure proper citations for all sources, including AI-generated content.

### How to Use

1. Clone this repository.
2. Replace `assets/titlepage.pdf` with the official title page template from MojaPG.
3. Modify `main.tex` to include your content.
4. Use LuaLaTeX to compile the document.
5. Ensure all citations are correctly included in `bibliography.bib`.

To properly generate the Table of Contents, bibliography and cross-references, you need to run the following commands:

```bash
lualatex main.tex
biber main
lualatex main.tex
lualatex main.tex
```

### Notes

- This template currently supports only Polish-language theses.
- If you find this template useful, please leave a ⭐ on this repository!
