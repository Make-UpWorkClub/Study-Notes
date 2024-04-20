---
grade: Sec5
subject: MAT
date: 2024-02-05 14:09
---

# Coniques

[Alloprof](https://www.alloprof.qc.ca/fr/eleves/bv/mathematiques/les-coniques-m1326)

![[Sections coniques.png|300]]

> [!abstract]+ Lieu géométrique
> Ensemble de points d'un espace géométrique qui sont caractérisés par une propriété métrique commune

^8b160e

## Cercle

[[Coniques#^8b160e|Lieu géométrique]] de tous les points dont la distance à *1* point (centre) est constante
Sous-ensemble de l’[[Coniques#Ellipse|ellipse]]

|          |        Forme générale         |        Forme canonique        |
| -------- |:-----------------------------:|:-----------------------------:|
| Équation | $x^2 + y^2 + Cx + Ey + F = 0$ | $(x - h)^2 + (y - k)^2 = r^2$ |
| $C$      |             $-2h$             |                               |
| $E$      |             $-2k$             |                               |
| $F$      |       $h^2 + k^2 - r^2$       |                               |

## Ellipse

[[Coniques#^8b160e|Lieu géométrique]] de tous les points dont la *somme* des distances à *2* points (foyers) est constante

Forme générale : $Ax^2 + By^2 + Cx + Ey + F = 0$ où $A$ et $B$ sont différents et de même signe
Forme canonique : $\cfrac{(x - h)^2}{a^2} + \cfrac{(y - k)^2}{b^2} = 1$
Longueurs des axes de symétrie : $2a, 2b$
$c^2 = |a^2 - b^2|$
Somme des distances aux foyers : $max(2a, 2b)$

## Parabole

[[Coniques#^8b160e|Lieu géométrique]] de tous les points dont la *somme* des distances à *1* point (foyer) et à une droite (directive) est constante
Courbe divergente crée par une section conique *parallèle*

|            | Forme canonique (verticale) | Forme canonique (horizontale) |
|:----------:|:---------------------------:|:-----------------------------:|
|  Équation  |   $(x - h)^2 = 4c(y - k)$   |    $(y - k)^2 = 4c(x - h)$    |
|   Sommet   |        $(h, k + c)$         |         $(h + c, k)$          |
| Directrice |         $y = k - c$         |          $x = h - c$          |

## Hyperbole

[[Coniques#^8b160e|Lieu géométrique]] de tous les points dont la *somme* des distances à *2* points (foyers) est constante
Courbe qui s’approche de deux asymptotes. Toujours en paire

Forme générale : $Ax^2 + By^2 + Cx + Ey + F = 0\text{ où }A B$

|            |                     Forme canonique                      |
|:----------:|:--------------------------------------------------------:|
|  Équation  | $\cfrac{(x - h)^2}{a^2} - \cfrac{(y - k)^2}{b^2} = \pm1$ |
| Asymptotes |                  $y = \pm\cfrac{b}{a}x$                  |
|   $c^2$    |                       $a^2 + b^2$                        |

> [!note]- Preuve des asymptotes
> $$
\begin{align}
\cfrac{x^2}{a^2} - \cfrac{y^2}{b^2} &= \pm 1 \\
\cfrac{y^2}{b^2} &= \cfrac{x^2}{a^2} \mp 1 \\
y^2 &= b^2(\cfrac{x^2}{a^2} \mp \cfrac{a^2}{a^2}) \\
y &= \sqrt{ \cfrac{b^2}{a^2}(x^2 \mp a^2) } \\
y &\approx \pm\cfrac{b}{a}x
\end{align}
$$