# Knowledge Bank

> Personal notes compiled from undergraduate coursework and self-study.
> Written in LaTeX using a unified template — built to last, not to be forgotten.

---

## Notes

| Title | Description | PDF |
|-------|-------------|-----|
| **Mathematics for the Slightly Rusty but Still Ambitious** | Linear Algebra · Multivariable Calculus · ODEs · Probability & Statistics | [math.pdf](./build/math.pdf) |
| **Machine Learning: A Field Guide for the Perpetually Confused** | Supervised & Unsupervised Learning · Theory · Interview Review | [ml.pdf](./build/ml.pdf) |
| **Computer Science: The Part They Expect You to Just Know** | Python · Data Structures · Algorithms · NP-Completeness | [cs.pdf](./build/cs.pdf) |

---

## Source Files

```
math.tex   — Mathematics
ml.tex     — Machine Learning
cs.tex     — Computer Science
```

Shared template components:

```
theorems.tex   — Coloured theorem/definition/example boxes (tcolorbox)
commands.tex   — Math shorthand macros
latexmkrc      — Build configuration (output → build/)
```

---

## Building

```bash
latexmk -pdf math.tex
latexmk -pdf ml.tex
latexmk -pdf cs.tex
```

Compiled PDFs are written to [`build/`](./build/).
