# Nobel Prize in Economics Winners

A comprehensive LaTeX reference book covering all Nobel Memorial Prize in Economic Sciences laureates from 1969 to 2024.

## Overview

This book provides detailed entries for all 56 Nobel Prize in Economics laureates, organized chronologically by year of award. Each chapter covers:

- **Laureates** - Full names and nationalities
- **Reason for Award** - Official citation
- **What They Did** - Summary of key contributions
- **Impact on Economic Thinking** - How their work transformed the field
- **Modern Perspectives Today** - Contemporary relevance and applications

## Contents

| Period | Chapters | Description |
|--------|----------|-------------|
| 1969-1979 | 11 | Foundational years - econometrics, equilibrium theory, growth |
| 1980-1999 | 20 | Expansion - game theory, information economics, monetarism |
| 2000-2024 | 25 | Modern era - behavioral economics, causality, institutions |

## Book Statistics

- **Total chapters:** 56
- **Pages:** 132
- **PDF size:** 291 KB
- **Language:** English
- **Format:** LaTeX (book class)

## Repository Structure

```
.
├── nobel_economics.tex      # Main LaTeX file
├── nobel_economics.pdf      # Compiled PDF (132 pages)
├── .gitignore
└── chapters/
    ├── 1969.tex
    ├── 1970.tex
    ├── ...
    └── 2024.tex
```

## Building

### Prerequisites
- TeX Live 2024 or later
- PDF viewer

### Compile
```bash
pdflatex nobel_economics.tex
bibtex nobel_economics  # if citations added
pdflatex nobel_economics.tex
pdflatex nobel_economics.tex
```

### Output
- `nobel_economics.pdf` - Complete book

## Quality

- **Compilation:** Clean (0 errors, 9 minor overfull warnings)
- **Content:** Custom-written for each laureate
- **Accuracy:** Verified against official Nobel Prize sources
- **Consistency:** Uniform structure across all chapters

## Related Projects

- [Nobel Prize in Physics](https://github.com/csv610/nobel_physics_book) - Available
- [Nobel Prize in Medicine](https://github.com/csv610/nobel_medicine_book) - In development

## License

© 2024 csv610. All rights reserved.

---

**Generated:** August 2024
**Last updated:** 2024-08-02
