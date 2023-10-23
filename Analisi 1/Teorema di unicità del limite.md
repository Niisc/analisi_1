#lezione7
Sia $a_{n}$ successore convergente a $l\in \mathbb{R}$ allora tale $l$ è unico

### Dimostrazione per assurdo
Sia $\lim_{ n \to \infty } a_{n}=l$ e $\lim_{ n \to \infty } a_{n} = m$ con $l \neq m$

Per la definizione di limite
$$\forall \varepsilon>0 \quad \exists n_{0} \in \mathbb{N} \quad|\quad \forall n \geq n_{0} \quad |a_{n}-l|<\varepsilon$$
$$\exists n_{1} \in \mathbb{N} \quad|\quad \forall n \geq n_{1} \quad |a_{n}-m|<\varepsilon$$

Poiché $l\neq m$ calcolo $|l-m|$ :
(usando la [[Numeri reali#Valore assoluto. Disuguaglianza triangolare|disuguaglianza triangolare]])
$$|l-m|=|l-a_{n}+a_{n}-m|=|(l-a_{n})+(a_{n}-m)|\leq |l-a_{n}|+|a_{n}-m|<2 \varepsilon$$
Quindi $\forall \varepsilon>0 \quad \forall n \geq max\{n_{0},n_{1}\} \quad |l-m|<2\varepsilon$ 
Ma questo è un assurdo perché se $l-m>0$ prendo come $\varepsilon=\frac{l-m}{8}$ e allora avrei:
$$l-m\leq 2 \cdot\frac{l-m}{8}=\frac{l-m}{4}$$
Che è assurdo (why??)

>[!Example] Esempio
$a_{n}$ non è convergente
Suppongo che esista $l\in \mathbb{R}$ $\lim_{n \to \infty}{a_{n}}=l$
$$\forall \varepsilon>0 \quad \exists n_{0} \in \mathbb{N} \quad | \quad \forall n \geq n_{0} \quad |n-l| < \varepsilon$$
$$-\varepsilon < n-l<\varepsilon$$
$$l-\varepsilon < n < \varepsilon + l$$
È un assurdo (why??) 
