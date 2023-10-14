#lezione1 
### Formulazione nel Linguaggio degli insiemi

Sia $S \in N$ sottoinsieme di $N$ tale che:
1) $0 \in S$ 
2) $\forall n\in S\Longrightarrow n+1 \in S$
Allora $S=N$
$$[(S\subseteq N)\wedge(0\in S)\wedge(\forall n\in S\Longrightarrow n+1\in S)]\Longrightarrow(S=N)$$
#### Principio del minimo intero
Ogni sottoinsieme non vuoto di $\mathbb{N}$ ha [[minimo]]

Falso in $\mathbb{Z}$
$A=\{z\in \mathbb{Z}: z<3\}$ 
### Forma equivalente
Sia $P(n)$ un [[predicato]] che dipende da $n \in \mathbb{N}$, suppongo [[che valgono]] le seguenti proprietà:
1) $P(0)$ è vero
2) $\forall n \in \mathbb{N} \quad P(n)$ vero $\Rightarrow$ $P(n+1)$ vero
Allora $P(n)$ è vero $\forall n \in \mathbb{N}$

Se $P(n)$ è vera per $\forall n \in \mathbb{N} \Rightarrow P(n+1)$ è vera, $P(n+1)$ è deducibile da $P(n)$

Assumo $P(n)$ vera ipotesi induttiva e come tesi $P(n+1)$
##### L'indice è muto
non importa l'indice con cui si inizia il principio di induzione