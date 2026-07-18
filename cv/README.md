# Emanuele Fabbiani CV

This directory contains the short and long variants of the CV, the minimal
vendored [Awesome-CV](https://github.com/posquit0/Awesome-CV) template, and
generated PDFs.

```text
cv/
├── long/       # Source for the three-page CV
├── short/      # Source for the one-page CV
├── output/     # Final PDF documents
└── template/   # Awesome-CV class and upstream license
```

Build it with:

```sh
cd cv
just
```

Alternatively, from the repository root, run `just --justfile cv/justfile`.

The final PDFs are written to `cv/output/emanuele_fabbiani_cv.pdf` and
`cv/output/emanuele_fabbiani_cv_long.pdf`. XeLaTeX build intermediates are
kept outside this directory under `tmp/latex`.
