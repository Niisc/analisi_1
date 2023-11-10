#lezione7
Sia $a_{n}$ successore convergente a $l\in \mathbb{R}$ allora tale $l$ è unico

#### Dimostrazione
Sia $\color{Fuchsia}\lim_{ n \to \infty } a_{n}=l$ e $\color{green}\lim_{ n \to \infty } a_{n} = m$ con $l \neq m$

Per la definizione di limite:
$$\forall \varepsilon>0 \quad  \begin{array}
 \\{\color{Fuchsia} \exists n_{0} \in \mathbb{N}} \quad|\quad \forall n \geq n_{0} \quad \color{Fuchsia}|a_{n}-l|<\varepsilon \\ \\
{\color{green}\exists n_{1} \in \mathbb{N}} \quad|\quad \forall n \geq n_{1} \quad \color{green} |a_{n}-m|<\varepsilon
\end{array}$$

Poiché $l\neq m$ calcolo $|l-m|$ :
(usando la [[Numeri reali#Valore assoluto. Disuguaglianza triangolare|disuguaglianza triangolare]])
$$|l-m|=|l-\underbrace{a_{n}+a_{n}}_{\text{stessa quantità}}-m|=\underbrace{|(l-a_{n})+(a_{n}-m)|\leq |l-a_{n}|+|a_{n}-m|}_{\text{Disuguaglianza triangolare}}<2 \varepsilon$$
Quindi $\forall \varepsilon>0 \quad \forall n \geq max\{n_{0},n_{1}\} \quad |l-m|<2\varepsilon$ 
Ma questo è un assurdo perché se $l-m>0$ prendo come $\varepsilon=\frac{l-m}{\color{orange}8}$ e allora avrei:
$${\color{Red}l-m}\leq 2 \cdot\frac{l-m}{8}=\color{Red}\frac{l-m}{4}$$
>[!warning] Attenzione
>In $\varepsilon=\frac{l-m}{\color{orange}8}$ il valore "8" al denominatore può essere sostituito da qualsiasi numero, era necessario che rimanesse la frazione per rendere evidente l'assurdo

>[!tip] Perché è un assurdo?
>Un numero positivo non può essere più piccolo di una frazione di se stesso

>[!Example] Esempio
$a_{n}$ non è convergente
Suppongo che esista $l\in \mathbb{R}$ $\lim_{n \to \infty}{a_{n}}=l$
$$\forall \varepsilon>0 \quad \exists n_{0} \in \mathbb{N} \quad | \quad \forall n \geq n_{0} \quad |n-l| < \varepsilon$$
$$-\varepsilon < n-l<\varepsilon$$
$$l-\varepsilon < n < \varepsilon + l$$
È un assurdo (why??) 
