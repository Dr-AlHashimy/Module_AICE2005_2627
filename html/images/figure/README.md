# SCEMS TikZiT Project

This project is structured for TikZiT.

- `tikzit.sty` — helper package to load TikZ libraries.
- `scems.tikzstyles` — styles for nodes/edges (edit in VS Code or TikZiT).
- `scems.tikzdefs` — optional TeX definitions (macros/colors).
- `figures/scems-risk-web.tikz` — the diagram (editable in TikZiT).
- `main.tex` — minimal LaTeX document that inputs the figure.

## How to use
1. Open `figures/scems-risk-web.tikz` in TikZiT to edit the diagram.
2. Edit styles in `scems.tikzstyles` (double-click style in TikZiT to jump).
3. Compile `main.tex` with `pdflatex` to produce the PDF.
