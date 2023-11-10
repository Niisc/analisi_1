![[Serie#Criterio del confronto di serie Criterio del confronto di serie]]

#### Dimostrazione
Considero le successioni delle somme parziali:
$$s_{k} = \sum^{\infty}_{n=0} a_{n} \quad t_{k} = \sum^{\infty}_{n=0} b_{n}$$
Poiché $a_{n} \leq b_{n} \quad \forall n \geq n_{0}$, allora $\forall k > n_{1}$:
$$s_{k} \leq t_{k}$$
1) Se $\sum^{\infty}_{n=0} b_{n}$ converge, allora $\lim_{ k \to \infty } t_{k} = t$
Per il [[Teorema del confronto di successioni]]
$$\lim_{ k \to \infty } s_{k} \leq \lim_{ k \to \infty } t_{k} = t$$
Ora $\sum^{\infty}_{n=0} a_{n}$ è a termini positivi: o converge o diverge.
$$\lim_{ n \to \infty } s_{k} \leq t \rightarrow \sum^{\infty}_{n=0} a_{n} \quad \text{converge}$$
2) Se $\sum^{\infty}_{n=0} a_{n}$ diverge, allora $\lim_{ k \to \infty } s_{k} = + \infty$
Per il [[Teorema del confronto di successioni]] 
$$\lim_{ k \to \infty } t_{k} \geq \lim_{ k \to \infty } s_{k} = + \infty$$
Ora $\sum^{\infty}_{n=0} b_{n}$ è a termini positivi: o converge o diverge
$$\lim_{ k \to \infty } t_{k} \geq + \infty \rightarrow \sum^{\infty}_{n=0} b_{n} \quad \text{diverge}$$
