Sia $a_{n}$ una [[Successioni|successione]] [[Successioni#Convergente|convergente]], allora $a_{n}$ è [[Successioni#Limitata|limitata]].
#### Dimostrazione
Suppongo $\lim_{ n \to +\infty }a_{n}=l \in \mathbb{R}$:
$$\forall \varepsilon >0\quad \exists n_{0} \in \mathbb{N}\ :\ \forall n \geq n_{0} \quad|a_{n}-l|<\varepsilon$$
Poiché vale $\forall \varepsilon>0$, vale anche per $\epsilon=1$
$$|a_{n}-l|<1$$
Sommo $|l|$ ad entrambi i membri:
$$|a_{n} -l|+|l| < 1 + |l|$$
Usando la [[Numeri reali#Valore assoluto. Disuguaglianza triangolare|disuguaglianza triangolare]]:
$$|a_{n}|=\underbrace{|a_{n}-l+l|\leq |a_{n}-l|+|l|}_{\color{green}\text{Disuguaglianza triangolare}} < 1+|l| \quad \color{orange}\forall n \geq n_{0}$$
Ovvero: $|a_{n}|\leq 1+|l|\quad \forall n \geq n_{0} \rightarrow a_{n}$ [[definitivamente]] [[Successioni#Limitata|limitata]] 
$$M=\max\{|a_{0}|;|a_{1}|;|a_{2}|;\dots;|a_{n-1}|;1+|l|\}$$
dove $M$ è il valore massimo tra i termini della successione e $1+l$
Per cui:
$$|a_{n}|\leq M \quad \forall n \in \mathbb{N}$$
quindi $a_{n}$ è limitata.
>[!attention] Attenzione
> Non vale il viceversa del teorema, cioè se una [[successioni|successione]] è [[Successioni#limi|limitata]] non è detto che ammette limite. Ad esempio: $a_{n} = (-1)^{n}$ non ammette limite ma è limitata tra -1 e 1.

