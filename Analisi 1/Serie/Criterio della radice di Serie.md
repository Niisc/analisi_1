![[Serie#Criterio della radice]]

#### Dimostrazione

$$b = \lim_{ n \to \infty } (a_{n})^{1/n}$$
Se $b >1$ il termine generale $a_{n}$ non tende a zero non vale la [[Condizione necessaria per la convergenza]], la serie diverge.

se $b < 1$ esiste $q \in \mathbb{R} \quad b<q<1$
$$\forall \varepsilon > 0 \quad \exists n_{0} \in \mathbb{N} : \forall n \geq n_{0} \quad |(a_{n})^{1/n} -b| < \varepsilon$$
$$b - \varepsilon < (a_{n})^{1/n} < b+\varepsilon < q + \varepsilon$$
$$\rightarrow (a_{n})^{1/n} < q+\varepsilon \rightarrow (a_{n}) < (q+\varepsilon)^{n}$$

Per $\varepsilon$ "piccolo" suppongo $(q+\varepsilon) <1$
Per il [[Criterio del confronto di serie]]:
$$(a_{n}) < b_{n} = (q + \varepsilon)^{n} \quad \text{con} \quad b_{n} \geq 0$$
Ora la serie
$$\sum^{\infty}_{n=0} b_{n} = \sum^{\infty}_{n=0} (a+\varepsilon)^{n}$$
È una [[Serie Geometrica]] di ragione $(q + \varepsilon)<1 \rightarrow$ convergente

$$\huge\text{Anche la serie: } \sum^{\infty}_{n=0} a_{n} \quad Converge.$$