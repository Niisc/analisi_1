#### Definizione
$$(a+b)^n=\sum_{k=0}^n {n \choose k}a^kb^{n-k}$$
Dove:
$\huge{n \choose k}$  [[Combinazioni]]
[[Sommatoria]] che somma $n+1$ elementi (poiché parte da 0)

> [!example] Esempio
>$$(a+b)^8 = \sum_{k=0}^8{8 \choose k}a^kb^{8-k}$$
>$$={8 \choose 0}a^0b^8+{8\choose 1}a^1b^7+....+{8\choose8}a^8b^0$$
>(I coefficienti sono ricavabili anche con il [[Triangolo di Tartaglia]])

#### Dimostrazione
Per ogni intero $n \geq 0$, con $a,b \in \mathbb{R}$
$$(a+b)^{n}= \sum^{n}_{k=0} {n\choose k} a^{k} b^{n-k}$$
Ora inizia la dimostrazione per [[Principio di induzione|induzione]]

Per $n=0$
$$(a+b)^{0} = \sum^{0}_{k=0} a^{0}b^{0} \quad \text{ovvero}\quad 1=1$$
Vero, sia vero per $n$, e dimostriamolo per $(n+1)$.
$$(a+b)^{n+1}=(a+b)(a+b)^{n}=$$
Per l'ipotesi induttiva
$$=(a+b)\sum^{n}_{k=0} {n \choose k} a^{k} b^{n-k} = \sum^{n}_{k=0} {n \choose k} a^{k+1} b ^{n-k} + \sum^{n}_{k=0} {n \choose k} a^{k} b^{n-k+1}=$$
Eseguendo nella prima sommatoria una [[Sommatoria#2) Traslazione di indici|traslazione di indici]]:
$$=\sum^{n+1}_{k=1} {n \choose k-1} a^{k} b^{n-(k-1)} + \sum^{n}_{k=0} {n \choose k} a^{k} b^{n-k+1}=$$
Scorporando l'addendo per $k=0$ dalla seconda sommatoria e quello per $k=n+1$ dalla prima
$$=a^{n+1} + \sum^{n}_{k=1} {n \choose k-1} a^{k}b^{n-k+1} + b^{n+1} + \sum^{n}_{k=1} {n \choose k} a^{k} b^{n-k+1}=$$
[[Sommatoria#5) Somma di sommatorie con stessi indici|sommando]] le due sommatorie:
$$=a^{n+1} + b^{n+1} + \sum^{n}_{k=1}  \left[{n \choose k-1} + {n \choose k}\right] a^{k} b^{n-k+1}=$$
Applicando la formula di ricorrenza ${n+1 \choose k} = {n \choose k-1} + {n \choose k}$
$$=a^{n+1} + b^{n+1} + \sum^{n}_{k=1} {n+1 \choose k} a^{k} b^{n-k+1}=$$
$$=\sum^{n+1}_{k=0} {n+1 \choose k} a^{k} b^{n-k+1}$$
Che è esattamente l'asserto voluto per $n+1$.
