---
date: 2025-01-21
tags:
  - Physics
  - Feynmann
cssclasses:
  - center-images
---
# Interacciones de la energía en la materia y cómo se convierte el calor en trabajo
***
Vivimos en un mundo de constantes interacciones termodinámicas, pero hay sistemas muy característicos que pueden solo pueden interactuar de cierta manera:
- **Sistema abierto:** Permite la transferencia de energía y masa.
- **Sistema cerrado:** Permite solo la transferencia de energía.
- **Sistema aislado:** No permite la transferencia de energía ni masa.

Como se mencionó [[Mecánica del Calor|anteriormente]], el [[Calor|calor]] y el [[Trabajo|trabajo]] pueden ser vistos como interacciones energéticas entre cuerpos, precisamente de esto trata la [[Primera Ley de la Termodinámica]], resumidamente dicta que el **cambio** de la energía interna de un sistema depende del calor y el trabajo.
$$\Delta U=Q-W$$

Resulta que más allá de la teoría. el calor y el trabajo se pueden convertir el uno en otro porque ambos son energía, esto se evidenció en el Experimento de Joule ($W\to Q$) y las [[Maquinas Térmicas|máquinas térmicas]] ($Q\to W$). Nos resulta interesante estudiar a estas últimas, las máquinas térmicas, porque gracias a ellas se dio la revolución industrial que nos llevó al desarrollo tecnológico que tenemos hoy en día.

![[Pasted image 20250123171325.png|150]]

$$Q_{h}=W+Q_{c}$$
Desde las locomotoras y máquinas de vapor, hasta los motores de combustión interna y las centrales nucleares más sofisticadas de hoy en día son máquinas térmicas. En ellas, se parte de un material a una temperatura elevada ($T_{h}$) que libera un calor $Q_{h}$, que la máquina absorbe y a través de un mecanismo convierte **parte** de ese calor en trabajo y el resto lo libera $Qc$ a un medio con temperatura $T_{c}$.

Es importante resaltar que no todo el calor se aprovecha para producir trabajo por las leyes de la naturaleza, siempre habrán pérdidas de energía en forma de calor $Q_{c}$, es aquí donde entra el concepto de [[Eficiencia de una Máquina Térmica|eficiencia térmica]] $n$, que no es más que un número que nos indica cuánto calor se convierte en trabajo. 

Fórmulas para calcularlo:
$$n=\frac{W}{Q_{h}} \quad n=1-\frac{Q_{c}}{Q_{h}}$$
Donde:
- $0\leq n<1$.
- El calor absorbido siempre será mayor que el trabajo y el calor liberado:
	- $Q_{h}>Q_{c}$
	- $Q_{h}>W$

En este orden de ideas es intuitivo pensar cuál sería la máquina térmica más eficiente. Esta es la [[Máquina de Carnot]], la cuál es una máquina ideal que define el límite máximo de eficiencia que una cierta máquina térmica puede alcanzar.
$$n \equiv \frac{T_{h}-T_{c}}{T_{h}} \Rightarrow n =1-\frac{T_{c}}{T_{h}}$$
