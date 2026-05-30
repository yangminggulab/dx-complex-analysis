# dx's Complex Analysis

## Preface

This may be the most personal of these books. I did not enter complex analysis through the feeling that it had many elegant theorems or clever integral tricks. I entered it through a simpler idea: complex numbers lift a problem into a richer plane.

Complex differentiability makes the mathematical world more structured. Results that first look magical, such as differentiability implying analyticity, boundary information controlling interior values, and local singular behavior determining contour integrals, become more natural once that structure is accepted.

## Why This Book Is Written This Way

I did not want complex analysis to become a standard notebook of formulas and theorems. The valuable part of the course is that it forces us to look seriously at mappings.

A complex number is not just an algebraic symbol. It is a point, a direction, a magnitude, and a rotation. Holomorphicity, conformality, branches, cuts, and residues all become clearer once the geometric picture returns.

## What This Book Keeps

The notes start from complex numbers, convergence, and completeness, then move into Cauchy-Riemann equations, analytic functions, complex integration, Cauchy's theorem, power series, zeros, singularities, and residues.

The deep line is the connection between algebraic language and geometric language: how a point in one plane is mapped to another, and which structures are preserved.

## Intended Readers

This book is for readers who are both attracted to and intimidated by complex analysis. It tries to turn the feeling of magic into a structure that can be entered step by step.

## Overall Roadmap

Following MIT OpenCourseWare complex variables, complex analysis is built around complex differentiability, which strongly constrains functions and leads to the complex plane, analytic functions, Cauchy theory, series expansions, and residue calculus. This tree matches the repository's notes on complex basics, Cauchy-Riemann equations, complex integration, power series, and residues.

```

## Repository Notes

- The main entry is `main.tex`.
- The body is currently concentrated in one main document covering foundations, Cauchy-Riemann equations, integration, power series, and residues.
- The repository also contains an ElegantBook template example; it is not the body of this book.
- For local compilation, running `xelatex main.tex` twice is usually enough.
