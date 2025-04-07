---
date: 2025-03-18
tags:
  - Concept
  - Math
---
> [!danger]  **Recursos**
> **Diapositivas:** [[05 Base y dimension.pdf]]
# Base
***
La base de un [[Espacio Vectorial|espacio]] o [[Subespacios Vectoriales|subespacio]] se define como el conjunto de vectores linealmente independientes que generan todo el espacio o subespacio, según corresponda.

Ejemplo:
	Los vectores $\hat{i},\hat{j},\hat{k}$ son los "vectores base" del sistema de coordenadas $x,y,z$. 
	Estos vectores se pueden usar para expresar como [[Combinación lineal]] cualquier vector de $\mathbb{R}{^3}$.

***
La **resolución de ejercicios** donde te pidan hallar la base de un subespacio de la forma:
$$H=\left\{\begin{pmatrix} a \\ b \\ c \end{pmatrix} \in \mathbb{R}{^3} : 2a+5b-c=0\right\}$$
Debes despejar cualquiera de las variables, a partir de la restricción, para obtener los vectores que son base de ese subespacio.

Si $n=dim(V)-\text{\# de restricciones}$, se debe dejar la combinación lineal expresada en términos de $n$ vectores. Por ejemplo, si mi espacio es $\mathbb{R}{^4}$ y tengo $1$ restricción, la cantidad de vectores que son base es $3$.

En nuestro caso al despejar $c=2a+5b$ y reemplazando en la forma dada queda que:
$$\begin{pmatrix} a \\ b \\ c \end{pmatrix}=\begin{pmatrix} a \\ b \\ 2a+5b \end{pmatrix}=a\begin{pmatrix} 1 \\ 0 \\ 2 \end{pmatrix}+b \begin{pmatrix} 0 \\ 1 \\ 5 \end{pmatrix}$$
Por ende, una base para este subespacio sería:
$$H=gen \left\{ \begin{pmatrix} 1 \\ 0 \\ 2 \end{pmatrix}, \begin{pmatrix} 0 \\ 1 \\ 5 \end{pmatrix} \right\}$$