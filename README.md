# Relevance of ISI B.Stat. Courses for Statistical ML & Sequential Analysis

This document evaluates the ISI Kolkata B.Stat. (Hons.) curriculum for a Master's student in ECE focusing on **theoretical statistical machine learning**, particularly **sequential analysis** and **adaptive decision-making**. Courses are grouped by relevance, and key textbooks are recommended for each.

---

## Summary Table: Course Relevance & Key Textbooks

| **Course**                                     | **Relevance**        | **Recommended Textbook**                                                                 |
|------------------------------------------------|-----------------------|------------------------------------------------------------------------------------------|
| **Probability Theory I–III**                   | Highly Relevant       | *W. Feller* – _Introduction to the Theory of Probability and Its Applications (Vol I & II)_ |
| **Introduction to Stochastic Processes**       | Highly Relevant       | *P.G. Hoel, S.C. Port, C.J. Stone* – _Introduction to Stochastic Processes_              |
| **Parametric Inference**                       | Highly Relevant       | *G. Casella, R.L. Berger* – _Statistical Inference (2nd Edition)_                        |
| **Nonparametric and Sequential Methods**       | Highly Relevant       | *E.L. Lehmann* – _Nonparametrics: Statistical Methods Based on Ranks_ + *A. Wald* – _Sequential Analysis_ |
| **Statistical Methods I–IV**                   | Moderately Relevant   | *L. Wasserman* – _All of Statistics_                                                    |
| **Linear Statistical Models**                  | Moderately Relevant   | *S.R. Searle* – _Linear Models_                                                          |
| **Design of Experiments**                      | Moderately Relevant   | *D.C. Montgomery* – _Design and Analysis of Experiments_                                 |
| **Real Analysis (I–III)**                      | Moderately Relevant   | *W. Rudin* – _Principles of Mathematical Analysis_                                       |
| **Vectors and Matrices (I–II)**                | Moderately Relevant   | *S. Axler* – _Linear Algebra Done Right_                                                 |
| **Numerical Analysis**                         | Moderately Relevant   | *S.D. Conte, C. de Boor* – _Elementary Numerical Analysis_                               |
| **Sample Surveys**                             | Not Relevant          | –                                                                                        |
| **Economic & Official Statistics / Demography**| Not Relevant          | –                                                                                        |
| **Statistical Quality Control & OR**           | Not Relevant          | –                                                                                        |
| **Discrete Mathematics**                       | Not Relevant          | –                                                                                        |
| **Elements of Algebraic Structures**           | Not Relevant          | –                                                                                        |
| **Differential Equations**                     | Not Relevant          | –                                                                                        |
| **Intro to Programming / Data Structures**     | Not Relevant          | –                                                                                        |
| **Design and Analysis of Algorithms**          | Not Relevant          | –                                                                                        |
| **Elective Courses in Sciences (Physics, Bio)**| Not Relevant          | –                                                                                        |

---

## Recommended Starting Point

| **Book**                    | **Author**           | **Why Recommended**                                                                 |
|----------------------------|----------------------|--------------------------------------------------------------------------------------|
| _All of Statistics_        | Larry Wasserman      | Covers foundational probability, inference, and modern ML topics. Ideal for transitioning from engineering to statistics. Accessible yet deep. |

---

A suggested flow for self-studying the core theoretical subjects, structured to build concepts progressively.

## Flowchart

## 📘 Flowchart (Concept Dependency Map)

```text
START
  |
  v
[Linear Algebra]       [Real Analysis]
       |                      |
       v                      v
 [Probability Theory I]     [Probability Theory II]
               |                      |
               v                      v
       [Probability Theory III] <-----
               |
               v
     [Statistical Methods I–IV]
               |
               v
     [Stochastic Processes]
               |
               v
     [Parametric Inference]
               |
               v
[Linear Statistical Models]   [Design of Experiments]
               \                 /
                v               v
     [Nonparametric & Sequential Methods]
                |
                v
     [Advanced Topics / Reading]

## Recommended Order (List Format)

1. **Linear Algebra** – Essential for everything from regression to PCA.
2. **Real Analysis** – Provides the rigorous math backbone for probability and inference.
3. **Probability Theory I → II → III** – Progressively builds measure-theoretic understanding.
4. **Statistical Methods I–IV** – Learn estimation, simulation, regression, and resampling.
5. **Stochastic Processes** – Foundation for modeling uncertainty, Markov chains, etc.
6. **Linear Statistical Models** – Theory behind regression, ANOVA, and least squares.
7. **Parametric Inference** – Core statistical inference tools: MLE, hypothesis testing.
8. **Design of Experiments** – Understand experimental planning and statistical efficiency.
9. **Nonparametric & Sequential Methods** – Distribution-free inference, adaptive testing.
10. **Advanced Reading** – Research papers, modern ML/stat textbooks, etc.

> Tip: Pair theoretical reading with implementation (e.g., simulations in Python/R).



> **Note**: This guide is based on the official 2016 ISI B.Stat. (Hons.) syllabus and curated for theoretical depth and relevance to sequential learning and statistical ML.
