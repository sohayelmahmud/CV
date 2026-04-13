# CV — S M A Nahian

LaTeX source and compiled PDFs for my curriculum vitae.

## Versions

| File | Description |
|------|-------------|
| `CV-short.tex` | 1–2 page CV (main version, used on website) |
| `CV-long.tex` | Full detailed CV |
| `CV-medium.tex` | Medium-length version |

Compiled PDFs are in [`docs/`](docs/) and built automatically via GitHub Actions on every push.

## Building locally

Requires a TeX Live installation:

```bash
pdflatex CV-short.tex
pdflatex CV-short.tex   # run twice for references
```

## Download

- [CV (Short)](docs/CV-short.pdf)
- [CV (Long)](docs/CV-long.pdf)
- [CV (Medium)](docs/CV-medium.pdf)
