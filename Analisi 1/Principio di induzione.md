#lezione1 

### Descrizione
Questo teorema si può applicare a teoremi che abbiano la struttura seguente:
"Per ogni $n \in \mathbb{N}, n\geq n_{0}$, vale la proprietà $p(n)$"

Il numero $n_{0}$ è il più piccolo intero per cui si vuole che la proprietà sia vera; se $n_{0}= 0$ il teorema afferma semplicemente che la proprietà è vera per ogni $n \in \mathbb{N}$.
La dimostrazione per induzione consiste nei due passi seguenti:
1) Si dimostra che $p(n)$ è vera per $n=n_{0}$ (primo passo induzione)
2) Si dimostra che, se $n$ è un generico numero naturale $\geq n_{0}$, dal fatto che $p(n)$ sia vera segue che $p(n+1)$ è vera.

>[!info]
Non importa l'indice con cui si inizia il principio di induzione ($n_{0}$). Generalmente è consigliato provare il numero minimo consentito nella condizione d'esistenza del problema.

### Formulazione nel Linguaggio degli insiemi

Sia $S \in N$ sottoinsieme di $N$ tale che:
1) $0 \in S$ 
2) $\forall n\in S\Longrightarrow n+1 \in S$
Allora $S=N$
$$[(S\subseteq N)\wedge(0\in S)\wedge(\forall n\in S\Longrightarrow n+1\in S)]\Longrightarrow(S=N)$$
