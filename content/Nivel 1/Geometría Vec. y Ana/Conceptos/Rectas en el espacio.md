# Rectas en el espacio
***
> Esquema explicativo: [[Rectas en el espacio.jpg]]

Suponga que $P(x_{0},y_{0},z_{0})$ es un punto conocido y $\vec{v}=(a,b,c)$ es un vector conocido.

Es posible encontrar una recta que sea paralela con el vector $v$ y contenga (o pase) por $P$.

$Q$ es un punto adicional sobre la recta cuyas ecuaciones son: $Q(x,y,z)$.

El vector $\vec{PQ}$ está completamente contenido en la recta, $\vec{PQ}$ es paralelo con $v$. Por ende, ambos vectores son [[Múltiplos de un Vector#^d78eb0|múltiplos]] uno del otro. 
$$\vec{PQ}=t\vec{v}$$
Donde $t$ es un número desconocido llamado *parámetro*, esta ecuación se llama **Ecuación Vectorial**.

 El valor de $\vec{PQ}$ se puede saber mediante:
$$\begin{align}\vec{PQ}=OQ-OP&=(x,y,z)-(x_{0},y_{0},z_{0}) \\\vec{PQ}&=(x-x_{0},y-y_{0},z-z_{0})\end{align}$$
Además, se sabe que $\vec{PQ}=tv$, entonces:

$$\begin{align}\vec{PQ}&=tv \\(x-x_{0},y-y_{0},z-z_{0})&=(ta,tb,tc)  \\ \\x-x_{0}&=ta \\ y-y_{0}&=tb \\ z-z_{0}&=tc\end{align}$$

Despejando x queda que:

$$\begin{align}&x=x_{0}+ta \\&y=y_{0}+tb \\&z=z_{0}+tc\end{align}$$

A esto último se le conoce como **ecuaciones paramétricas de la recta**. 
	Fórmula en los libros: $Q=P+tv$.

Si ahora despejamos $t$ de cada ecuación encontramos que:
$$\frac{x-x_{0}}{a}=\frac{y-y_{0}}{b}=\frac{z-z_{0}}{c}$$
A esta forma se le conoce como **ecuación simétrica de la recta**. pero se debe tener cuidado, ya que si alguno de los valores del vector $v$ es cero, no es posible expresarla de esta manera.
