# k-distance-superset-state-2

Manuscript repository for

> **Fast Greedy Heuristics with Linear-Time Redundant Removal and Local
> Swap for the Minimum $k$-Dominating Set Problem on Large-Scale
> Networks.**
> Tho Chi Luong — International School, Vietnam National University,
> Hanoi.

## Contents

- `paper.tex` — LaTeX source (XeLaTeX, English body + Vietnamese
  abstract / keywords).
- `paper.pdf` — Compiled PDF, 19 pages.

## Build

The source uses XeLaTeX (Unicode-native, required for the Vietnamese
abstract).

```bash
xelatex paper.tex
xelatex paper.tex     # second pass for cross-references
```

A TeX distribution such as MiKTeX or TeX Live is sufficient; the
`fontspec` package is required (bundled with both).
"# k-distance-superset-state-2" 
