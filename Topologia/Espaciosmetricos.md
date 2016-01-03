---
title: Ejercicios - Espacio métrico
author: Diego Asterio de Zaballa
source: Topología, Rafael Lopez Camino
geometry: "a4paper, top=2.5cm, bottom=2.5cm, left=3cm, right=3cm"
fontsize: 10pt
header-includes:
  \usepackage{tikz}
---

### Ejercicio 2.1

Dado un espacio métrico $(X,d)$, se define:

$\centering d'(x,y) = \frac{d(x,y)}{1 + d(x,y)}$

Probar que $d'$ es una distancia en $X$ y estudiar si es equivalente a $d$. Observar que $d'$ es una distancia acotada, pues 
$d' \l 1$.

#### Solución

$d'(x,y) = \frac{d(x,y)}{1 + d(x,y)}$ como $d(x,y) \geq 0$ cumpliendo la igualdad si y solo si $x = y \quad d'(x,y) \geq 0$ 
y se cumple que $ d'(x,y) = 0 \Leftrightarrow d(x,y) = 0 \Leftrightarrow x = y$.

También cumple que $d'(x,y) = \frac{d(x,y)}{1 + d(x,y)} = \frac{d(y,x)}{1 + d(y,x)} = d'(y,x)$.

Y por último cumple que si 
