Siano date $a_{n}, b_{n}, c_{n}$ successioni  tali che 
$$lim_{n \to \infty}{a_{n}}=l=lim_{n \to \infty}{c_{n}}$$
se esiste $\bar{n} \in \mathbb{N} \quad | \quad \forall n \geq\bar{n}$  si abbia $a_{n} \leq b_{n} \leq c_{n}$
allora $b_{n}$ è convergente a $l$ ovvero $lim_{n \to \infty}{b_{n}}=l$

### Dimostrazione
$$\forall \varepsilon >0 \quad \exists n_{0} \in \mathbb{N} \quad |\quad \forall n \geq n_{0} \quad |a_{n}-l| < \varepsilon$$
$$\exists n_{1} \in \mathbb{N} \quad | \quad \forall n \geq n_{1}\quad | \quad |c_{n} -l| < \varepsilon$$

$\forall n \geq max\{n_0,n_1\}$ si ha:
$$l-\varepsilon < a_{n}< l+\varepsilon$$$$l-\varepsilon < c_{n}< l+\varepsilon$$
Sappiamo che $\exists \bar{n} \in \mathbb{N} \quad \forall n \geq \bar{n} \quad a_{n}\leq b_{n} \leq c_{n}$ 
quindi per ogni $n\in \mathbb{N} \quad n \geq max\{n_{0},n_{1}\}$ si ha
$$l-\varepsilon < a_{n} \leq b_{n} \leq c_{n} < l + \varepsilon$$
ovvero $\forall \varepsilon >0 \quad \exists \tilde{n}=max\{\bar{n},n_{0},n_{1}\} \quad \forall n > \tilde{n}$ si ha
$$l-\varepsilon < b_{n}<l+\varepsilon \rightarrow |b_{n}-l|<\varepsilon$$

Quindi $b_{n}$ converge a $l$


