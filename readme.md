# Unique Akari Puzzle Construction and Human-Solvability with ASP

This repository contains the **master's thesis** exploring Akari puzzle construction and human-solvability using Answer Set Programming (ASP) integrated with Python. All key ASP code and Python pseudocode are included within the thesis document itself.

## Project Overview

Akari, or Light Up, is a logic puzzle requiring unique solutions. This thesis presents an ASP-based constructor that generates unique Akari puzzles from 6×6 up to 14×14 grids (largest feasible for unique puzzles: 12×12). A human strategy-based solver is implemented using six major deduction strategies.

Some generated puzzles, though unique, were not solvable using only the human strategies. To address this, the constructor was redesigned with explicit human-solvability constraints, ensuring every accepted puzzle can be solved by these strategies. This focus on human accessibility increases construction time, limiting the practical maximum human-solvable grid to 10×10.

Performance analysis, solver walkthroughs, and a comparison to a C++ Akari framework are provided. The thesis contains detailed pseudocode and ASP logic for all algorithms used.

## Repository Contents

- **thesis.pdf**  
  - Full MSc thesis:
    - Puzzle construction logic 
    - Human-solving strategies
    - Results on uniqueness and human-solvability
    - Performance and scalability evaluation
    - Case study solution
    - Comparative analysis with a C++ implementation

## Code Availability

No separate code files are provided due to institutional agreements, but **all relevant ASP and Python pseudocode are included within the thesis** for reference and understanding.

For questions or collaboration requests, please contact [Urmee Pal](mailto:urmeeacademicmsc@gmail.com).


## Citation

If referencing this project, please cite the thesis (see file included).

*Thank you for your understanding regarding code redistribution.*
