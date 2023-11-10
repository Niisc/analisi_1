![[Serie#Criterio del confronto asintotico di serie]]

#### Dimostrazione
Dato che $\lim_{ n \to \infty } \frac{a_{n}}{b_{n}} =1$

$$\forall \varepsilon > 0 \quad \exists n_{0} \in \mathbb{N} : \forall n \geq n_{0} \quad \left |\frac{a_{n}}{b_{n}} -1 \right| < \varepsilon$$
$$1-\varepsilon < \frac{a_{n}}{b_{n}} < 1 + \varepsilon$$
Poiché $b_{n} \geq 0$:
$$(1-\varepsilon)b_{n} < a_{n} < (1+\varepsilon)b_{n}$$
Per il [[Criterio del confronto di serie]] si ha che:

1) $(1-\varepsilon) b_{n} < a_{n}$ 
se: $\sum^{\infty}_{n=0} a_{n}$ converge $\rightarrow \sum^{\infty}_{n=0} b_{n}$ converge
se: $\sum^{\infty}_{n=0} b_{n}$ diverge $\rightarrow \sum^{\infty}_{n=0} a_{n}$ diverge

2) $a_{n} < (1+\varepsilon) b_{n}$
se: $\sum^{\infty}_{n=0} b_{n}$ converge $\rightarrow \sum^{\infty}_{n=0} a_{n}$ converge
se: $\sum^{\infty}_{n=0} a_{n}$  diverge $\rightarrow \sum^{\infty}_{n=0} b_{n}$ diverge

>[!example] Esempio
> $$\sum^{\infty}_{n=0} \frac{1}{n^{2}}$$
