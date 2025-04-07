# Base y Exponente Variable
***
Para resolver estos casos se aplica el siguiente procedimiento:

Sea $y=f(x){^{g(x)}}$.

Tomamos **logaritmo natural** a ambos lados:
$$\begin{align}\ln y &=\ln f(x){^{g(x)}} \\\ln y &=g(x) \cdot \ln f(x)\end{align}$$
Ahora tomamos el límite cuando $x \rightarrow a$ a ambos lados:
$$\lim_{x\to a}\ln y=\lim_{x\to a}g(x)\cdot\ln f(x)$$
> El límite de la derecha es una indeterminación tipo $0 \cdot \infty$, que se puede resolver.

Suponiendo que: 
$$\lim_{x\to a}g(x)\cdot\ln f(x)=L$$
entonces:
$$\lim_{x\to a}\ln y=L$$
Ahora:
$$\ln(\lim_{x\to a}y)=L$$
Luego:
$$e^{\ln(\lim_{x\to a}y)}=e^L$$
Por lo que:
$$\lim_{x\to a}y=e^{L}$$
