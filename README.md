# Braid Theory – Algebraic Structures and Algorithms

This repository contains a research project submitted for the undergraduate course *Algebraic Structures*, part of the 4th year in the double degree in Computational Mathematics and Software Engineering.

The report explores the algebraic structure of braid groups, focusing on Artin's presentation and algorithmic methods for braid manipulation and reduction.

## Structure

1. Braid groups: definitions and properties  
2. Artin's relations  
3. Algorithms: Braid Combing and Handle Reduction

## Build

To compile the LaTeX document:

```bash
latexmk -pdf main.tex
biber main
latexmk -pdf main.tex
latexmk -pdf main.tex
````

## Citation

```bibtex
@misc{braid_theory_2024,
  title        = {Braid Theory – Algebraic Structures and Algorithms},
  author       = {Alina Rojas Reynoso, Mar Iborra Granel},
  year         = {2024},
  note         = {Undergraduate research project, Algebraic Structures (4th year, Computational Mathematics and Software Engineering)},
  howpublished = {\url{https://github.com/alinarojas/braid-theory}},
  doi          = {10.5281/zenodo.15599942}
}
```
