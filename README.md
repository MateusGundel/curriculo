# 📄 Mateus Gündel — Resume

My professional resume built in LaTeX — clean, single-page, and easy to edit.

🔗 [LinkedIn](https://www.linkedin.com/in/mateusgundel/)

## 🛠️ How to Compile

### Prerequisites

- A LaTeX distribution installed (e.g., [TeX Live](https://www.tug.org/texlive/), [MiKTeX](https://miktex.org/), or [MacTeX](https://www.tug.org/mactex/))
- Required packages: `fontawesome5`, `titlesec`, `enumitem`, `hyperref`, `tabularx`, `multicol`, `parskip`

### Build

```bash
pdflatex resume.tex
```

The output will be generated as `resume.pdf`.

## 📁 Structure

```
├── resume.tex    # Main LaTeX source
├── resume.pdf    # Compiled resume
├── .gitignore    # Ignores LaTeX build artifacts
└── README.md
```

## ✏️ Editing

All content is in a single `resume.tex` file — just edit and recompile. No external templates or dependencies needed.
