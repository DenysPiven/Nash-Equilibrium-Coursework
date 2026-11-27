# Distributed Nash Equilibrium Search Algorithms — Coursework (2021)

3rd-year coursework, Taras Shevchenko National University of Kyiv, Faculty of Computer Science and Cybernetics, Department of Computational Mathematics. Kyiv, 2021.

- **Author:** Denys Piven (3rd year, group OM-3)
- **Supervisor:** Prof. Volodymyr Semenov, Dr. Sc. (Phys.-Math.)
- **Language:** Ukrainian

## Abstract

An introduction to game theory and Nash equilibrium (classification of games, the prisoner's dilemma, normal-form games, the "Harvard" game, "Guess the number"), followed by two distributed Nash equilibrium search algorithms (continuous-time dynamics and a linearly convergent algorithm) and a numerical study of them on these example games.

The work was extended into the bachelor's thesis [Distributed-Nash-Equilibrium-Bachelor-Thesis](https://github.com/DenysPiven/Distributed-Nash-Equilibrium-Bachelor-Thesis), which also contains the C# program used for the experiments.

## Contents

```
thesis/Distributed_Nash_equilibrium_search_algorithms_coursework.pdf   coursework text
tex/main.tex                                                           LaTeX source
tex/*.png                                                              figures
```

Build the PDF from source (XeLaTeX/pdfLaTeX with Ukrainian babel):

```
cd tex && pdflatex main.tex && pdflatex main.tex
```
