# Why CMLL Has 42 Cases

This repository contains a short mathematical note explaining why the CMLL step
in the Roux method admits exactly 42 equivalence classes.

The argument proceeds in two stages:

1. We show that, under the standard CMLL constraints (fixed bottom corners and a fixed
   set of six edges), every top-layer corner configuration with arbitrary permutation
   and total twist zero is globally admissible. This yields a state space of size
   \(4! \cdot 3^3 = 648\).

2. We then quotient this state space by a natural symmetry action and apply
   Burnside’s lemma to compute the number of equivalence classes, obtaining exactly 42.

The emphasis is on group-theoretic reasoning and global reachability, rather than on
explicit solving algorithms or move sequences.

## Contents

- `paper/main.tex` — LaTeX source
- `paper/main.pdf` — compiled PDF

## Notes

This note concerns global reachability of cube states satisfying the CMLL constraints.
It does not address reachability via sequences of moves that preserve the Roux blocks
throughout the solve.
