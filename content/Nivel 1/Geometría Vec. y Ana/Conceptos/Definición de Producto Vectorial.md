# Definición de Producto Vectorial
***

> [!warning] Nota
> El producto vectorial solo está definido en vectores $R{^3}$, es decir, de tres dimensiones.

El procedimiento para encontrar el producto vectorial o también conocido como producto cruz se establece así:

*Para este ejemplo usaremos los vectores $\vec{a}=(-2,1,3)$ y $\vec{b}=(0,-2,4)$*

**Paso 1:** Armar una matriz donde la **primera fila** lleve las letras $i,j,k$ (cada una representa a $x,y,z$ respectivamente), la **segunda fila** los valores del primer vector $a$ y la **tercera fila** los valores del segundo vector.

$$a\times b=\begin{bmatrix}i & j & k \\-2 & 1 & 3 \\0 & -2 & 4\end{bmatrix}$$

**Paso 2:** Usar el método de [[Determinante#^095456|Inversa por Cofactores]] sobre la primera fila para hallar el resultado del producto vectorial.
$$a\times b=\begin{bmatrix}i & j & k \\-2 & 1 & 3 \\0 & -2 & 4\end{bmatrix}=+\left(4-(-6)\right)i-\left(-8-0\right)j+\left(4-0\right)k$$
> Ir tapando y resolviendo el [[Determinante#Matrices 2x2|det de la 2x2]] restante.
> ![[inversa cof ejemplific.png]]

**Paso 3:** Hacer las operaciones restantes y dar el resultado final.
$$a\times b=10i+8j+4k=(10,8,4)$$

