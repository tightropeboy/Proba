# Proba

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tightropeboy/Proba/HEAD?labpath=TD1EX3%2Fcode.ipynb)

## Variables aléatoires discrètes

|                   | **Bernoulli** |**Binomial**   | **Géométrique**  |  **Poisson**  | **Uniforme**  | **Hypergéométrique**  |
|        -          |       -       |       -       |        -         |       -       |       -       |          -            |
| ${\bf X(\Omega)}$     | ${0, 1}$     | $\{0, 1, 2, \dots, n\}$ | $\{ 1, 2, \dots, n\}$ | $\mathbb{N}$ | $\{a, \dots, n\}$ | - |
| $\textbf{Notation}$   | $X \sim B(p)$ | $X \sim B(p, n)\\p\in\space]0, 1[$ | $X \sim Geom(p)$ | $X \sim P(\lambda)\\\lambda > 0$ | $X \sim U(X(\Omega)) $ | - |
| $\textbf{Loi}$        | $\begin{cases}P(k=0) = 1 - p\\P(k=1) = p\end{cases}$ | $P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}p^k(1-p)^{n-k}$ | $P(X=k) = (1-p)^{k-1}.p$ | $P(X=k) = e^{-\lambda}.\frac{(\lambda^k)}{k!}$ | $P(X=k) = \frac{1}{n}$ | - |
| ${\bf E(X)}$          | $p$ | $n.p$ | $\frac{1}{p}$ | $\lambda$ | $\frac{n+1}{2}$ | $n.p$ |
| ${\bf V(X)}$          | $p\space(1-p)$ | $n.p.(1-p)$ | $\frac{1-p}{p²}$|$\lambda$ | $\frac{n²+1}{12}$ | - |
| ${\bf \sigma(X)}$           | $\sqrt{p\space(1-p)}$ | $\sqrt{n.p.(1-p)}$ | $\frac{\sqrt{1-p}}{p}$ | $\sqrt{\lambda}$ | $\sqrt{\frac{n²+1}{12}} $ | - |
