#lezione1 
## Formulazione nel Linguaggio degli insiemi
#### Sia $S \in N$ sottoinsieme di $N$ tale che:
1) $0 \in S$ 
2) $\forall n\in S\Longrightarrow n+1 \in S$
Allora $S=N$
$$[(S\subseteq N)\wedge(0\in S)\wedge(\forall n\in S\Longrightarrow n+1\in S)]\Longrightarrow(S=N)$$
#### Principio del minimo intero
Ogni sottoinsieme non vuoto di $N$ ha [[minimo]]
##### Falso in 
$Z\qquad A=\{z\in Z\quad:\quad z<3\}$ 
$Q,R$ 
## Forma equivalente
Sia $P(n)$ un [[predicato]] che dipende da $n \in N$, suppongo [[che valgono]] le seguenti proprietà:
1) $P(0)$ è vero
2) $\forall n \in N\quad P(n)$ vero $\Rightarrow$ $P(n+1)$ vero
Allora $P(n)$ è vero $\forall n \in N$
### Se $P(n)$ è vera per $\forall n \in N \Rightarrow P(n+1)$ è vera, P(n+1) è deducibile da P(n)
Assumo P(n) vera (**_ipotesi induttiva_**) e come tesi P(n+1)
#### L'indice è muto
non importa l'indice con cui si inizia il principio di induzione


## Forma equivalente
Sia $P(n)$ un [[predicato]] che dipende da $n \in N$, suppongo [[che valgono]] le seguenti proprietà:
1) $P(n_0)$ è vero con $n_0 \in N$
2) $\forall n \geq n_0\quad P(n)$ vero $\Rightarrow$ $P(n+1)$ vero
Allora $P(n)$ è vero $\forall n \geq n_0$ 
