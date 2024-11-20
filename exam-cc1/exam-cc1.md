---
header-includes:
  - \usepackage{mathrsfs}
---
![PNS](https://raw.githubusercontent.com/pns-mam/mi1/master/logo-pns.png)

## MAM3

# Mathématiques de l'ingénieur.e 1
# 2024-25
# Exam CC no. 1

**Durée 2H00. Documents non autorisés. Tous les exercices sont indépendants.
Le barème prévisionnel est indiqué pour chaque exercice.**

**Rendre sur des copies séparées les exercices 1 et 2 d'une part, 3 et 4 d'autre part.** 

# Exercice 1 (4 points)
Montrer que l'intégrale impropre ci-dessous est convergente et déterminer sa valeur :

$$ \int_0^1 \ln x\,\mathrm{d}x. $$

# Exercice 2 (4 points)
Calculer

$$ \int_D \frac{x\ \mathrm{d}x\mathrm{d}y}{y+x^2} $$

où $D := \lbrace (x,y) \in \mathbf{R}^2\ |\ 0 \leq x \leq 1,\ 1 \leq y \leq 3 \rbrace$.

# Exercice 3 (6 points)
On considère la famille de parties de $[0,3]$ suivante :

$$ \mathscr{A} := \lbrace [0,1], [0, 2] \rbrace. $$

## 3.1
Montrer que les tribus engendrées sur $[0,3]$ par $\mathscr{A}$ et

$$ \tilde{\mathscr{A}} := \lbrace [0,1], ]1,2] \rbrace $$

sont égales.

**Réponse.** Comme $]1,2] = [0,2] \cap \complement [0,1] \in \mathscr{B}(\mathscr{A})$,
on a $\tilde{\mathscr{A}} \subset \mathscr{B}(\mathscr{A})$,
donc $\mathscr{B}(\tilde{\mathscr{A}}) \subset \mathscr{B}(\mathscr{A})$.
Réciproquement, $[0,2] = [0,1] \cup ]1,2] \in \mathscr{B}(\tilde{\mathscr{A}})$,
donc $\mathscr{B}(\mathscr{A}) \subset \mathscr{B}(\tilde{\mathscr{A}})$.

## 3.2
Donner, sans le justifier, le cardinal de la tribu $\mathscr{B}(\mathscr{A})$ engendrée sur $[0,3]$ par $\mathscr{A}$.

**Réponse.** Le cardinal est $2^3 = 8$. (D'après ce qui précède, la tribu est engendrée par la partition
$\lbrace [0,1],]1,2],]2,3] \rbrace$ de $[0,3]$.)

## 3.3
Soit $(X,\mathscr{B})$ un espace mesurable, et soit $f : X \to [0,3]$ telle que $f^{-1}([0,1])$ et $f^{-1}([0,2])$ appartiennent tous deux à $\mathscr{B}$. Que peut-on dire de $f$ ? 

**Réponse.** Par hypothèse, les images réciproques de parties de $\mathscr{A}$ sont mesurables, donc l'application est mesurable de $(X,\mathscr{B})$ dans $[0,3]$ muni de la tribu engendrée par $\mathscr{A}$.

# Exercice 4 (6 points)

## 4.1
Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_{-\infty}^\infty x\cos(x/n)e^{-x^2}\,\mathrm{d}x,\quad n \geq 1. $$

**Réponse.** Ayant posé

$$ f_n(x) := x\cos(x/n)e^{-x^2},\quad x \in \mathbf{R},\quad n \geq 1, $$

on voit que chaque $(f_n(x))_n$ tend vers $xe^{-x^2}$ (converge simple) quand $n$ tend vers l'infini et que

$$ |f_n(x)| \leq |x|e^{-x^2} $$

dont le second membre est une application intégrable. Par CV dominée, la limite vaut donc (intégrande impair)

$$ \int_{-\infty}^\infty x e^{-x^2}\,\mathrm{d}x = 0. $$

## 4.2
Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_0^n \frac{e^{-x}\sin x\,\mathrm{d}x}{1 + \sin^2(x/n)}\,,\quad n \geq 1. $$

**Réponse.** Ayant posé

$$ f_n(x) := \frac{e^{-x}\sin x\,\chi_{|[0,n]{x}}{1 + \sin^2(x/n)},\quad x \geq 0,\quad n \geq 1, $$

on voit que chaque $(f_n(x))_n$ tend vers $e^{-x}\sin x$ (converge simple) quand $n$ tend vers l'infini et que

$$ |f_n(x)| \leq e^{-x} $$

dont le second membre est une application intégrable sur $\mathbf{R_+}$. Par CV dominée, la limite vaut donc

$$ \int_0^\infty e^{-x}\sin x\,\mathrm{d}x = \frac{1}{2}. $$

## 4.3
Déterminer, si elle existe, la limite quand $n$ tend vers l'infini de la suite

$$ \int_0^n \frac{n\,\mathrm{d}x}{n(1 + \cos^2 x) + 1}\,,\quad n \geq 1. $$

**Réponse.** Ayant posé

$$ f_n(x) := \frac{1}{1 + \cos^2 x + 1/n}\chi_{|[0,n]{x}},\quad x \geq 0,\quad n \geq 1, $$

on voit que cette suite de fonctions mesurables et positives est croissante, et que chaque $(f_n(x))_n$ tend
vers $1/(1 + \cos^2 x)$ quand $n$ tend vers l'infini. Par CV monotone, la limite est donc $+\infty$ puisque

$$ \int_0^\infty \frac{\mathrm{d}x}{1 + \cos^2 x} \geq \int_0^\infty \frac{\mathrm{d}x}{2} = \infty. $$