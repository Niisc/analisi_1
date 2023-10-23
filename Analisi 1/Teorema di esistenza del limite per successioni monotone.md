#lezione7 

Data una [[Successioni|successione]] $a_{a}$ monotona crescente, allora $a_{a}$ ammette [[limite]] $l=sup(\{a_{n}\})$ 

Tale limite è finito (e quindi $a_{n}$ converge a $l$) se $a_{n}$ aumenta superiormente, altrimenti si pone il limite pari a $+\infty$ (e quindi $a_{n}$ è divergente a $+\infty$ )
(Analogo enunciato per $a_{n}$ monotona decrescente)
$l = inf(\{a_{n}\})$
### Dimostrazione
*Ipotesi*: $a_{n}$ monotona crescente $\forall n \in \mathbb{N} \quad a_{n+1} \geq a_{n}$

Superiormente limitata $\exists m \in \mathbb{R} \quad | \quad \forall n \in \mathbb{N} \quad a_{n} \leq m$

$\{a_{n}\}$ è un insieme di numeri reali

$a_{n}$ è limitata superiormente (ha dei maggioranti) quindi ammette estremo superiore ${sup(\{a_{n}\})}$ è finito per la definizione di estremo superiore:
$$\forall n \in \mathbb{N} \quad a_{n} \leq sup(\{a_{n}\}) \rightarrow a_{n} -sup(\{a_{n}\}) \leq0$$

Tuttavia $\forall \varepsilon >0 \quad sup(\{a_{n}\}) - \varepsilon$  non deve essere maggiorante: quindi deve esistere $n_{0} \in \mathbb{N} \quad | \quad a_{n_{0}} > sup(\{a_{n}\})-\varepsilon$

![[Teorema di esistenza del limite per successioni monotone 2023-10-14 17.32.58.excalidraw]]

$a_{n}$ è crescente e quindi:
$$a_{n_{0}} < a_{n_{0}+1} < a_{n_{0}+2} < \ldots \rightarrow a_{n_{0}} < a_{n}\quad \forall n \geq n_{0}$$

Sappiamo che:
$$a_{n} -sup(\{a_{n}\}) \leq 0$$
$$a_{n} > sup(\{a_{n}\}) - \varepsilon$$
ovvero che $a_{n} \geq n_{0}$ 
$$sup(\{a_{n}\})-\varepsilon<a_{n}<sup(\{a_{n}\})<sup(\{a_{n}\})+\varepsilon$$
riscriviamo $\forall \varepsilon > 0 \quad \exists n_{0} \in \mathbb{N} \quad|\quad \forall n\geq n_0$

Ovvero $lim_{n \to \infty} a_{n}=sup(\{a_{n}\})$ cioè $a_{n}$ converge a $sup(\{a_{n}\})$ 


> [!info] Osservazione
Non basta che una successione sia limitata per la convergenza; ad esempio: $a_{n}=(-1)^{n}$ è limitata ma irregolare.

