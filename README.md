# 📚 Final Project: Commutative Algebra

![Subject](https://img.shields.io/badge/Subject-Commutative%20Algebra-blue?style=for-the-badge&logo=latex&logoColor=white)
![University](https://img.shields.io/badge/Institution-VNUHCM%20US-green?style=for-the-badge)
![Year](https://img.shields.io/badge/Year-2024--2025-orange?style=for-the-badge)

> **A comprehensive study and solution set for key concepts in Commutative Algebra, including Hilbert's Nullstellensatz, Ideal Theory, and Noetherian Rings.**

## 📌 Project Overview

This repository contains the source code (LaTeX) and final report for the **Commutative Algebra** final project. The project explores fundamental and advanced topics in algebra, demonstrating theoretical understanding through rigorous proofs and solving specific problems in polynomial rings and integer rings.

**Key Topics Covered:**
* **Hilbert's Nullstellensatz:** Detailed proof and corollaries regarding maximal ideals in $\mathbb{C}[x_1, ..., x_n]$.
* **Ideal Theory:** Primary ideals, Prime ideals, Maximal ideals, and Primary Decomposition.
* **Noetherian Rings:** Properties, Hilbert's Basis Theorem, and connections to localization.
* **Ring Extensions & Quotients:** Analysis of structures like $\mathbb{C}[x,y]/\langle x^2+y^2-1\rangle$ and $\mathbb{Z}[x]/\langle x^3-2x+1\rangle$.

## 👨‍🎓 Author Information

* **Student:** Pham Van Nghia
* **Student ID:** 22110130
* **Institution:** Faculty of Mathematics and Computer Science, University of Science, VNU-HCM.

---

## 📂 Repository Structure

```text
final-project_Communicative-Algebra/
├── main.tex             # Main LaTeX source file
├── Reference.bib        # Bibliography / Citations
├── images/              # (Optional) Figures and diagrams used in the report
└── README.md            # Project documentation
```

## 📖 Contents Summary

1. **Hilbert's Nullstellensatz**
* Investigation of maximal ideals in polynomial rings over algebraically closed fields.
* The correspondence between maximal ideals and common zeros of polynomials.
2. **Theoretical Problems** 
* **Quotient Rings:** Construction and examples (e.g., $\mathbb{Z}/3\mathbb{Z}$).
* **Primary Ideals:** Definition, properties, and the relation $\sqrt{I} = P$.
* **Noetherian Rings:** Equivalence definitions, Hilbert's Basis Theorem, and Cohen's Theorem.
3. **General & Individual Problems** 
* Proofs regarding radicals of ideals: $\sqrt{IJ} = \sqrt{I} \cap \sqrt{J}$.
* Analysis of rings of fractions (Localization) $S^{-1}R$.
* **Specific Problem 1:** Determining maximal ideals of $R = \mathbb{C}[x,y]/\langle x^2+y^2-1\rangle$.
* **Specific Problem 2:** Analyzing the structure and ideals of $R = \mathbb{Z}[x]/\langle x^3-2x+1\rangle$.

## 🛠️ Tech Stack & Compilation
This document is written in LaTeX to ensure high-quality mathematical typesetting.
### Prerequisites
* TeX distribution (TeX Live, MikTeX, or Overleaf).
* BibTeX for reference management.
### How to Compile
If you clone this repository to your local machine, you can compile the PDF using the following commands:
```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
**Note:** Multiple runs are required to resolve cross-references and bibliography.
## 📚 References
The project references standard texts in the field:

1. R. Y. Sharp, Steps in Commutative Algebra.
2. M. F. Atiyah and I. G. Macdonald, Introduction to Commutative Algebra.
3. Trinh Thanh Deo, Modern Algebra Textbook.