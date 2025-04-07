---
date: 2025-04-05
tags:
  - Topic
---
> [!danger]  **Recursos**
> **Diapositivas:** [[04 Dependencia e independencia lineal.pdf]]
> 
# Linealmente Dependientes o Independientes (L.I. o L.D.)
***
>C.L. $=\vec{0}$ --> LD      C.L. $\neq\vec{0}$ --> LI
>Es LD si **no todos** los escalares son $0$, si todos son $0$ = LI.

> [!info] Definición Formal
> Los vectores $\vec{v_{1}},\vec{v_{2}},\dots,\vec{v_{n}}$ de un [[Espacio Vectorial]] $V$, se dice que son **Linealmente dependientes**, si existen $n$ escalares $\alpha_{1},\alpha_{2},\dots\alpha_{n}$ **no todos cero**, tales que:
> $$\alpha_1\vec{v_1}+\alpha_2\vec{v_2},\cdots,\alpha_n\vec{v_n}=\vec{0}$$
> En caso contrario, diremos que el conjunto de vectores $\vec{v_{1}},\vec{v_{2}},\dots,\vec{v_{n}}$ es linealmente independiente.
> 
> En otras palabras, un conjunto de vectores es **L.I.** si la única combinación lineal de los vectores$\vec{v_{1}},\vec{v_{2}},\dots,\vec{v_{n}}=\vec{0}$, es la combinación lineal trivial, es decir, $\alpha_{1}=\alpha_{2}=\cdots=\alpha_{n}=0$, de lo contrario es **L.D.**
## L.D. - Linealmente Dependiente
***
Se dice que un vector es **Linealmente Dependiente** bajo dos circunstancias:
- Cuando en un plano los vectores sean paralelos o nulos.
- Cuando en el espacio el vector sea [[Combinación lineal|combinación lineal]] de los otros dos vectores.
*[[Espacio generado|¿Qué pasa con el espacio generado de estos dos casos?]]*

Básicamente este nuevo vector se vuelve redundante y no aporta nada al subespacio generado, es decir, cuando puedas quitar ese vector sin alterar el subespacio generado el vector se considera **linealmente dependiente**.

Otra forma de decirlo es que este vector se puede expresar como combinación lineal de los otros puesto que ya hacía parte del subespacio generado.
$$\det(A)=0$$
## L.I. - Linealmente Independiente
***
Si el vector añade una dimensión nueva al subespacio generado se dice que este vector es **Linealmente Independiente**.
$$\det(A)\neq 0$$

Cuando al reducir la matriz hayan igual número de filas que de pivotes es LI, si hay menos pivotes que filas es LD 