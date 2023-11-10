#### Definizione
Sia $V$ un insieme e $\mathbb{K}$ un [[Struttura algebrica#Campo|campo]], su cui sono definite un'operazione interna detta somma vettoriale:

$$+ : V \times V \to V$$
$$(v_{1},v_{2}) \to v_{1}+ v_{2}$$
Ed un operazione esterna detta prodotto per uno scalare:
$$\cdot : \mathbb{K} \times V \to V$$
$$(t,v) \to t \cdot v$$
 La [[Struttura algebrica|struttura algebrica]] $(V,\mathbb{K},+,\cdot)$ si dice spazio vettoriale se:
 1) $(V,+)$ è un [[Struttura algebrica#Gruppo abeliano|gruppo abeliano]], con elemento neutro ed inverso di $v$ denotati rispettivamente $0$ e $-v$;
 2) La moltiplicazione per uno scalare è distributiva rispetto alla somma in vettoriale. cioè $t \cdot (v_{1}, v_{2}) = (t \cdot v_{1})+ (t \cdot v_{2})$ per ogni $t \in \mathbb{K}$ e $v_{1},v_{2} \in V$
 3) La moltiplicazione per uno scalare è distributiva rispetto alla somma in $\mathbb{K}$, cioè $(t_{1}+t_{2}) \cdot v =(t_{1} \cdot v)+(t_{2}\cdot v)$ per ogni $t_{1},t_{2} \in \mathbb{K}$ e $v \in V$
 4) La moltiplicazione per uno scalare è omogenea rispetto alla moltiplicazione in $\mathbb{K}$, cioè $t_{1} \cdot(t_{2} \cdot v)=(t_{1}t_{2}) \cdot v$ per ogni $t_{1},t_{2} \in \mathbb{K}$ e $v\in V$
 5) La moltiplicazione per uno scalare soddisfa la proprietà di normalizzazione, ovvero $1 \cdot v = v$ per ogni $v \in V$

Gli elementi $v$ di $V$ si dicono vettori.

#### Proprietà
Sia $(V,\mathbb{K},+, \cdot )$ uno spazio vettoriale e siano $u,v,w \in V$ e $t \in \mathbb{K}$ allora:
1) Vale la proprietà di cancellazione della somma, ovvero $u+v = u+w$ se e solo se $v=w$
2) Vale la proprietà do annullamento del prodotto, ovvero $t \cdot v =0$ se e solo se $t=0$ o $v=0$
3) L'elemento neutro $0$ e l'inverso additivo di $v$ sono unici. In particolare, l'inverso è uguale a $-1 \cdot v$

## Omomorfismi
Siano $(V,\mathbb{K}, +_{v} , \cdot_{v})$ e $(V, \mathbb{K}, +_{w}, \cdot_{w})$ due spazi vettoriali sul medesimo campo. Allora la funzione $f : V \to W$ è un omomorfismo di spazi vettoriali, o [[applicazioni lineari|applicazione lineare]], se per ogni $v, \tilde{v} \in V$ e $t \in \mathbb{K}$, vale:
1) $$f(v + _{v} \tilde{v}) = f(v) +_{w} f(\tilde{v})$$
2) $$f(t \cdot_{v} v)=t \cdot_{w} f(v)$$
>[!attention] Attenzione
L'insieme delle applicazioni lineari da $V$ in $W$ viene indicato con $\hom(V,W)$
