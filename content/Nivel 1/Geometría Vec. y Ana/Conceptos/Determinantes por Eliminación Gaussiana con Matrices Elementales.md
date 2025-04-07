# Determinantes por Eliminación Gaussiana con Matrices Elementales
***
$$A=\begin{bmatrix}2&3&0\\2&4&0\\0&0&1\end{bmatrix}$$
**Paso 1:** Hacer el procedimiento de [[Eliminación Gaussiana]] hasta obtener una [[Matriz triangular superior e inferior|matriz triangular superior]].
$$A=\begin{bmatrix}2&3&0\\2&4&0\\0&0&1\end{bmatrix}\frac{E_{12}}{\to}\begin{bmatrix}2&4&0\\2&3&0\\0&0&1\end{bmatrix}\frac{\frac{1}{2}E_1}{\to}\begin{bmatrix}1&2&0\\2&3&0\\0&0&1\end{bmatrix}\frac{-2E1+E2}{\to}\begin{bmatrix}1&2&0\\0&7&0\\0&0&1\end{bmatrix}=T$$
**Paso 2:** Calcular el determinante de la matriz original $A$ con ayuda de [[Propiedades de las Matrices Elementales#Propiedad 6|esta]] propiedad.
$$det(A)=\frac{det(T)}{det (F_{12})det (F_{1}(1/2)) det(F_{12}(-2))}=\frac{-1}{(-1)(\frac12) (1)}=\frac{-1}{-\frac12}=2$$

***

Este procedimiento es muy útil para matrices de orden 4x4 en adelante.