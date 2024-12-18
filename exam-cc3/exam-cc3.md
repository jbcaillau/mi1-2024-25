![PNS](https://raw.githubusercontent.com/pns-mam/mi1/master/logo-pns.png)

## MAM3

# Mathématiques de l'ingénieur.e 1
# 2024-25
# Exam CC no. 3

**Durée 2H00. Documents non autorisés. Tous les exercices sont indépendants. Le barème prévisionnel est indiqué pour chaque exercice.**

**Rendre sur des copies séparées les exercices 1 et 2 d'une part, 3 et 4 d'autre part.** 

# Exercice 1 (7 points)

## 1.1

Soit $A > 0$, montrer que

$$ I_A := \int_0^A \frac{\sin x\,\mathrm{d}x}{x} $$

est bien définie.

## 1.2

Montrer que

$$ I_A = \int_0^A \sin x \left( \int_0^\infty e^{-tx}\,\mathrm{d}t \right) \mathrm{d}x. $$

## 1.3

Montrer qu'on peut appliquer le théorème de Fubini pour calculer $I_A$.

## 1.4

En déduire que

$$ I_A = C + \textrm{Im} \int_0^\infty \frac{e^{A(i-t)}}{i-t}\,\mathrm{d}t $$

où $C$ est une constante que l'on précisera.

## 1.5

Montrer que

$$ \left| \int_0^\infty \frac{e^{A(i-t)}}{i-t}\,\mathrm{d}t \right| \leq \frac{1}{A} $$

et en déduire que $I_A$ possède une limite que l'on précisera quand $A$ tend vers l'infini.

# Exercice 2 (5 points)

## 2.1 

Soit $f_n(x) := (-1)^n e^{-2^n x}$, $x \geq 0$, $n \geq 0$. Montrer que

$$ \sum_{n \geq 0} \int_0^\infty |f_n(x)|\,\mathrm{d}x < \infty. $$

## 2.2

En déduire que l'intégrale ci-dessous est bien définie : 

$$ \int_0^\infty \sum_{n \geq 0} f_n(x)\,\mathrm{d}x. $$

## 2.3

Déterminer la valeur de cette intégrale.

# Exercice 3 (5 points)

## 3.1 

Montrer que le produit de convolution des deux fonctions caractéristiques $\chi_{[0,1]} * \chi_{[0,2]}$ est bien défini, puis le calculer.

## 3.2

Soit $a > 0$, déterminer la transformée de Fourier de $\chi_{[0,a]}$.

## 3.3

Déterminer la transformée de Fourier de $\chi_{[0,1]} * \chi_{[0,2]}$.


# Exercice 4 (4 points)

## 4.1

Soient $m$ et $\sigma$ deux réels, $\sigma > 0$, et soit

$$ I = \frac{1}{\sigma\sqrt{2\pi}} \int_{\mathbf{R}} e^{-(x-m)^2/(2\sigma^2)}\,\mathrm{d}x. $$

Effectuer le changement de variable $x = \varphi(y) := \sigma y + m$ dans cette intégrale, puis en déduire sa valeur. 

[**Indication** : on pourra retrouver cette valeur à l'aide du théorème de Fubini.]

## 4.2

Soit $X$ une variable aléatoire à valeurs dans $\mathbf{R}$ de densité

$$ f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-(x-m)^2/(2\sigma^2)}. $$

On pose $Y = \varphi^{-1}(X)$, donner l'espérance de $Y$.
