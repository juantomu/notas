---
date: 2025-01-21
tags:
  - Physics
  - Feynmann
cssclasses:
---
# ¿Cómo se describe el movimiento de una rueda?
***
Entender el concepto de traslación en un círculo implica establecer una relación entre moverse alrededor de un círculo y hacerlo en línea recta.

Al desplazarse sobre una circunferencia suceden dos fenómenos importantes:
- **Velocidad:** en todo momento yo me estaré desplazando hacia una dirección dentro de la circunferencia, esto se puede ver como un vector de velocidad $\vec{v}$ tangente a nuestro punto de ubicación sobre la circunferencia.
- **Fuerza:** al mismo tiempo experimentaremos una fuerza de **aceleración** $\vec{a}$ que nos atrae al centro de la circunferencia, pero que no realiza [[Trabajo|trabajo]] por ser perpendicular a nuestra dirección de movimiento.

Además, por las propiedades de una circunferencia todo par de elementos de esta posee una cantidad de movimiento que se anula, ya que cada punto de una rueda tiene una fuerza perfectamente compensada por una fuerza recíproca que lo atrae al centro, un sentido de rotación y un punto sobre el eje opuesto que posee un sentido contrario de rotación.

![[Pasted image 20250121121245.png|200]] ![[Pasted image 20250121121321.png|225]]

Con esto ya podemos introducir el concepto de [[Distancia recorrida|distancia recorrida]], donde podemos medir la distancia que nos hemos desplazado dentro de la circunferencia.
$$S=r \theta$$

Otro factor fundamental que se puede medir es nuestra [[Desplazamiento angular|posición y desplazamiento angular]] calculando la diferencia entre el ángulo final e inicial 
$$\Delta \theta=\theta_{f}-\theta_{0}$$

Aquí viene un concepto clave y es la diferencia entre la [[Velocidad Media|velocidad lineal]] $v$ y la [[Velocidad angular|velocidad angular]] $\omega$. La velocidad lineal como su nombre indica describe un movimiento en línea recta, mientras que la velocidad angular describe cuánto ha girado un cuerpo al rededor de una circunferencia. 
$$\omega_m\equiv\frac{\theta_f-\theta_i}{t_f-t_i}=\frac{\Delta\theta}{\Delta t}$$
Estas dos velocidades se relacionan bajo la fórmula:
$$v=r \omega$$
Resulta que entender esto es fundamental, puesto que dos puntos sobre una misma circunferencia pero con radios distintos pueden tener la misma velocidad angular, pero no la misma velocidad lineal.

![[Pasted image 20250121133320.png|400]]

En este movimiento la velocidad angular puede variar y de aquí nace la [[Aceleración angular|aceleración angular]] $\alpha$.
$$\alpha_m\equiv\frac{\omega_f-\omega_i}{t_f-t_i}=\frac{\Delta\omega}{\Delta t}$$
Esta aceleración angular también tiene su relación con la [[Aceleración Media|aceleración tangencial]]
$$a_{t}=r\alpha$$
y sucede lo mismo que con la velocidad, dos puntos con diferente radio en una misma rueda pueden tener aceleraciones distintas.

Si despejamos las formulas de velocidad y aceleración angular en función de sus valores finales, obtendremos respectivamente:
- **Ángulo final:** $\theta_{f}=\theta_{0}+\overline{\omega}t$
- **Velocidad final:** $\omega_{f}=\omega_{0}+\alpha t$

La ecuación cinemática que describe al completo este movimiento rotacional se describe a continuación [(explicación)](https://youtu.be/idPPeTjPn3w?t=215):
$$\theta_{\mathrm{f}}=\theta_{0}+\omega_{0}t+\frac{1}{2}\alpha t^{2}$$
Existe otro concepto interesante para describir el movimiento circular uniforme llamado [[Inercia rotacional]]. Esta propiedad describe cuán difícil es cambiar el estado de rotación de un objeto. Depende de la masa del objeto y la distribución de la misma, cuanto más lejos esté el centro de masa del eje de rotación, mayor será el momento de inercia (más difícil será ponerlo a girar).
$$I=mr{{^2}}$$
Este estado de inercia nos permite a su vez describir la conservación del [[Momento angular]], análogo del [[Momento Lineal|momento lineal]], donde el estado de movimiento circular está regido por la velocidad angular y la inercia rotacional.
$$L=I \omega$$
Es por esto último que se presenta el fenómeno de las [bailarinas de ballet](https://www.youtube.com/watch?v=l5VgOdgptRg).

