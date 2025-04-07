---
date: 2025-03-21
tags:
  - Concept
  - Math
---
> [!danger]  **Recursos**
> **Diapositivas:** [[06 Cambio de Base.pdf]]
> **Video:** [Matriz de Transición](https://www.youtube.com/watch?v=UgDhSfpNPQo)
# Cambio de Base
***
Como los espacios vectoriales pueden tener infinitas bases, resulta conveniente tener un método que convierta los vectores de coordenadas escritos en una base $B_{1}$ a vectores de coordenadas en otra base $B_{2}$.

Para realizar este procedimiento necesitamos las dos bases $B_{1}$ y $B_{2}$ que nos interesan del espacio vectorial a trabajar.
## Matriz de transición
***
La matriz de transición, denotada por $M_B^A$, se halla:

- **Paso 1:** Escribir los vectores de la base de origen $A$ como combinación lineal de los vectores de la base $B$.
- **Paso 2:** Resolver la combinación lineal y el sistema de ecuaciones resultante para cada vector de la base $A$. 
- **Paso 3:** Los escalares resultantes serán los vectores columna de la matriz de transición. Por ende, $(x,y,z)_{B}=\begin{pmatrix} \alpha \\ \beta \\ \gamma \end{pmatrix}$, en palabras sería: *el vector de la base $A=(x,y,z)$ en términos de la base $B$ es el vector columna $(\alpha, \beta, \gamma)$.*
- **Paso 4:** Por último, la matriz de transición $M_B^A$ son los escalares escritos como vector columna.

> Para **hallar un vector $\vec{v}$ en la base canónica**, basta con realizar la combinación lineal donde los vectores son los de una base $B$ del espacio y los escalares serían las componentes del vector $[\vec{v}]_{B}$.
> 
> Esto ocurre porque **las coordenadas de un vector en una base específica representan los coeficientes de la combinación lineal de los vectores de esa base.**
> 
> $$[\vec{v}]_{B}=\begin{pmatrix}\alpha \\ \beta\end{pmatrix}=\alpha(\vec{b}_{1})+\beta(\vec{b}_{2})$$
> donde, $\vec{b}_{1}$ y $\vec{b}_{2}$ son los vectores de la base $B$.
> 
> *Míralo como que al hacer la combinación lineal de un vector en una base con los vectores de esa misma base se cancela la base en la que estás y te queda el vector expresado en la canónica.*
### Propiedades de la Matriz de Transición
***
Si quisiéramos pasar de la base $B$ a la $A$ podríamos hacer el mismo procedimiento, o por propiedad de este procedimiento, si ya tenemos la matriz de cambio de base $M_B^A$, su inversa es la matriz que nos permite volver de $M_A^B$.

$$(M_B^A){^{-1}}=M_A^B$$ 
> Para convertir un vector de la base $A$ a la base $B$ solo bastaría con multiplicarlo por la matriz de transición $M_B^A$.
> $$M_B^A[\overline{v}]_A=[\overline{v}]_B$$