# Relativistic Quantum Waves

A -somewhat- comprehensive educational paper on relativistic quantum wave mechanics.

## Contents

- `relativistic-quantum-waves.tex` - Main LaTeX source file
- `relativistic-quantum-waves.pdf` - Compiled PDF document
- `templates/` - LaTeX templates and custom macros used in this project

## Building

To compile the document:

```bash
pdflatex relativistic-quantum-waves.tex
```

You may need to run it twice to get the table of contents and references correct.

## Templates

The `templates/` directory contains custom LaTeX configurations:
- `preamble.tex` / `preamble_no.tex` - Document preamble configurations
- `macros.tex` / `macros_no.tex` - Custom LaTeX macros
- `letterfonts.tex` - Font configurations
- `template.tex` - Basic template example

## Contributing

If you find any mistakes or want to contribute corrections, please:
1. Use the templates provided to maintain consistent styling
2. **Important**: Add any LaTeX build artifacts to `.gitignore` to keep pull requests clean

Build artifacts include: `*.aux`, `*.log`, `*.toc`, `*.fdb_latexmk`, `*.fls`, `*.synctex.gz`, etc.
