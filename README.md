# Proba

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tightropeboy/Proba/HEAD?labpath=TD1EX3%2Fcode.ipynb)

## Variables aléatoires discrètes

<table>
    <tr>
        <td></td>
        <td>**Bernoulli**</td>
        <td>**Binomial**</td>
        <td>**Géométrique**</td>
        <td>**Poisson**</td>
        <td>**Uniforme**</td>
        <td>**Hypergéométrique**</td>
    </tr>
    <tr>
        <td>${\bf X(\Omega)}$</td>
        <td>${0, 1}$</td>
        <td>$\{0, 1, 2, \dots, n\}$</td>
        <td>$\{ 1, 2, \dots, n\}$</td>
        <td>$\mathbb{N}$</td>
        <td>$\{a, \dots, n\}$</td>
        <td>-</td>
    </tr>
    <tr>
        <td>$	extbf{Notation}$</td>
        <td>$X \sim B(p)$</td>
        <td>$X \sim B(p, n)\\p\in\space]0, 1[$</td>
        <td>$X \sim Geom(p)$</td>
        <td>$X \sim P(\lambda)\\\lambda > 0$</td>
        <td>$X \sim U(X(\Omega)) $</td>
        <td>-</td>
    </tr>
    <tr>
        <td>$\textbf{Loi}$</td>
        <td>$\begin{cases}P(k=0) = 1 - p\\P(k=1) = p\end{cases}$</td>
        <td>$P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}p^k(1-p)^{n-k}$</td>
        <td>$P(X=k) = (1-p)^{k-1}.p$</td>
        <td>$P(X=k) = e^{-\lambda}.\frac{(\lambda^k)}{k!}$</td>
        <td>$P(X=k) = \frac{1}{n}$</td>
        <td>-</td>
    </tr>
    <tr>
        <td>${\bf E(X)}$</td>
        <td>$p$</td>
        <td>$n.p$</td>
        <td>$\frac{1}{p}$</td>
        <td>$\lambda$</td>
        <td>$\frac{n+1}{2}$</td>
        <td>$n.p$</td>
    </tr>
    <tr>
        <td>${\bf V(X)}$</td>
        <td>$p\space(1-p)$</td>
        <td>$n.p.(1-p)$</td>
        <td>$\frac{1-p}{p²}$</td>
        <td>$\lambda$</td>
        <td>$\frac{n²+1}{12}$</td>
        <td>-</td>
    </tr>
    <tr>
        <td>${\bf \sigma(X)}$</td>
        <td>$\sqrt{p\space(1-p)}$</td>
        <td>$\sqrt{n.p.(1-p)}$</td>
        <td>$\frac{\sqrt{1-p}}{p}$</td>
        <td>$\sqrt{\lambda}$</td>
        <td>$\sqrt{\frac{n²+1}{12}} $</td>
        <td>-</td>
    </tr>
</table>