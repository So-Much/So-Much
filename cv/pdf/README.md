# CV PDF files

| File | Source |
|------|--------|
| `Experience_en.pdf` | `Experience_en.tex` |
| `Project_en.pdf` | `Project_en.tex` |

Vietnamese PDFs (`Experience_vi.pdf`, `Project_vi.pdf`) can be added later when compiled.

## Update workflow

```powershell
pdflatex Experience_en.tex
Move-Item -Force Experience_en.pdf cv\pdf\

pdflatex Project_en.tex
Move-Item -Force Project_en.pdf cv\pdf\
```

Or compile in Overleaf and download into this folder.
