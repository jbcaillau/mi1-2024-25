---
header-includes:
  - \usepackage{mathrsfs}
---
![PNS](https://raw.githubusercontent.com/pns-mam/mi1/master/logo-pns.png)

## MAM3

# Mathématiques de l'ingénieur.e 1
# 2024-25
# Exam CC no. 2

**Durée 2H00. Documents non autorisés. Tous les exercices sont indépendants.
Le barème prévisionnel est indiqué pour chaque exercice.**

**Rendre sur des copies séparées les exercices 1 et 2 d'une part, 3 et 4 d'autre part.** 

# Exercice 1 (6 points)

## 1.1

Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_{-\infty}^\infty |x|\cos((x+1)/n)e^{-x^2}\,\mathrm{d}x,\quad n \geq 1. $$

## 1.2

Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_0^n \frac{n \mathrm{d}x}{n + x^2}\,,\quad n \geq 1. $$

## 1.3

Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_e^\infty \frac{n \sin(x/n)}{x^2 \ln^2 x}\,\mathrm{d}x,\quad n \geq 1. $$

# Exercice 2 (5 points)

## 2.1

Montrer que la fonction

$$  F(t) := \int_0^\infty \frac{\cos(tx)e^{-x}}{1+x^2}\,\mathrm{d}x $$

est bien définie pour $t \in \mathbf{R}$.

## 2.2

Montrer que la fonction $F$ est deux fois dérivable, et donner les expressions de $F'$ et $F''$.

## 2.3

En déduire que $F$ vérifie l'équation différentielle

$$ F''(t) - F(t) = G(t),\quad t \in \mathbf{R}, $$

avec $G$ une fonction dont on donnera une expression explicite.

# Exercice 3 (4 points)

## 3.1

Soient $f \in L^p(X,\mathscr{B},\mu)$ et $g \in L^q(X,\mathscr{B},\mu)$, avec $1/p + 1/q = 1/r$ et $p$, $q$, $r$ dans
$]0,\infty[$, $r \geq 1$. Montrer que $fg$ appartient à $L^r(X,\mathscr{B},\mu)$ et que

$$ \|fg\|_r \leq \|f\|_p \|g\|_q. $$

[Indication : noter que $1/(p/r) + 1/(q/r) = 1$, et que $f^r$ est dans $L^{p/r}$. ]

## 3.2

Soient $f_1 \in L^{p_1}(X,\mathscr{B},\mu)$, ..., $f_n \in L^{p_n}(X,\mathscr{B},\mu)$, avec $1/p_1 + \cdots + 1/{p_n} = 1/r$ et $p_1,\dots,p_n$,
$r$ dans $]0,\infty[$, $r \geq 1$. Montrer que $f_1 \cdots f_n$ appartient à $L^r(X,\mathscr{B},\mu)$ et que

$$ \|f_1 \cdots f_n\|_r \leq \|f_1\|_{p_1} \cdots \|f_n\|_{p_n}. $$


# Exercice 4 (5 points)

## 4.1

Soient $\beta > \alpha > 0$. Monter que l'intégrale

$$ I := \int_0^\infty \frac{e^{-\alpha x} - e^{-\beta x}}{x}\,\mathrm{d}x $$

est bien définie.

## 4.2

Montrer que

$$ I := \int_0^\infty (\int_\alpha^\beta e^{-tx}\,\mathrm{d}t)\,\mathrm{d}x. $$

## 4.3

En déduire $I$.
