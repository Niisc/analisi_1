#lezione13 #finire 
#####  Definizione
Una [[Serie]] $\sum^{\infty}_{n=0} a_{n}$ si dice a segno variabile se è formata da infiniti termini positivi e infiniti termini negativi.
## Criterio di Leibniz 
$$\sum^{\infty}_{n=n_{0}} (-1)^{n} a_{n}$$
$a_{n} \geq 0 \quad \forall n \in \mathbb{N}$
$a_{n} \to 0 \quad n \to + \infty$
$a_{n} \text{ decrescente} \quad \forall n \in \mathbb{N}$

Quindi
$$\sum^{\infty}_{n=n_{0}} (-1)^{n} a_{n} \quad \text{converge}$$
> [!example] Esempio
> $$\sum^{\infty}_{n=1} (-1)^{n} \frac{3}{n }$$
> (da finire)

Sia data la serie $$\sum_{n=0}^{\infty}(-1)^{n}a_{n} \qquad a_{n}\ge_{0} \forall n$$

di indice:
1) Pari, approssimano la somma per eccesso
2) Dispari, approssimano la somma per difetto

Il resto della serie è maggiorato, in valore assoluto, dal primo termine trascurato.
In formule:
$$s_{2n}=\sum_{k=0}^{2n}(-1)^{k}a_{k} \downarrow s$$$$s_{2n+1}=\sum_{k=0}^{2n+1}(-1)^{k}a_{k} \uparrow s$$
$$|Rn|=\left|\sum_{k=n}^{\infty}(-1)^{k}a_{k}\right| \le a_{n}$$