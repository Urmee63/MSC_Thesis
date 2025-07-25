# Akari Puzzle Construction and Human-Solvability with ASP

This repository contains the **master's thesis** investigating Akari puzzle construction and human-solvability using Answer Set Programming (ASP) integrated with Python. All code and sensitive assets are withheld due to institutional agreements; only the thesis document is shared.

## Project Overview

Akari, or Light Up, is a logic puzzle requiring unique solution grids. This thesis presents an ASP-based constructor that generates unique Akari puzzles for grids from 6×6 up to 14×14 (largest feasible: 12×12 for classic uniqueness). A human strategy-based solver is implemented, capturing six deduction strategies used by human players. 

Initially, some generated puzzles, while unique, proved unsolvable by the human strategy-based solver. The constructor was thus redesigned to embed explicit human-solvability constraints, guaranteeing that all accepted puzzles can be solved using the six strategies. This human-oriented generation incurs a notable construction-time increase, with the largest practical grid size for this method being 10×10.

Performance, human accessibility, and a comparison with an established C++ Akari puzzle framework are presented, along with a case study illustrating the deduction process on a 10×10 puzzle.

## Repository Contents

- **thesis.pdf**  
  Contains the full MSc thesis with:
    - Puzzle construction algorithms and ASP modeling
    - Definition and implementation of human-solving strategies
    - Results on puzzle uniqueness and human-solvability
    - Performance and scalability analysis
    - Comparative study with C++ implementation
    - Case study solution walkthroughs

## Code Availability

Project code and data are **not publicly available** due to NDA limitations with the supervising institution. Code may be shared in the future following review and sanitization.

For inquiries or collaboration, please contact [Urmee Pal](urmeeacademicmsc@gmail.com).

## Citation

If referencing this work, please cite the thesis included here.

*Thank you for your understanding regarding code availability.*
