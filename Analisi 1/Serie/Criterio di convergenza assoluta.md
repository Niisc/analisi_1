![[Serie#2) Condizione sufficiente alla convergenza ( Criterio di convergenza assoluta )]]

>[!info] Osservazione
>la disuguaglianza può essere vista come una generalizzazione della disuguaglianza triangolare


#### Dimostrazione
$a_{n}$ non termini di segno costante
**Per ipotesi $\sum^{+\infty}_{n=0}|a_{n}|$ è convergente

$a_{n}=a_{n}+|a_{n}|-|a_{n}|$ 

$a_{n}={\color{green}(}a_{n}+|a_{n}|{\color{green})}-|a_{n}|$

Quindi: $$\sum^{+\infty}_{n=0} a_{n}=\sum^{+\infty}_{n=0} {\color{green}(} a_{n}+|a_{n}|{\color{green})}-\color{orange}\underbrace{\sum^{+\infty}_{n=0} |a_{n}|}_{\text{converge per HP}}$$
$$\text{La serie } \sum^{+\infty}_{n=0} \text{converge} \iff \text{converge} \sum^{+\infty}_{n=0} {\color{green}(} a_{n}+|a_{n}|{\color{green})} $$
$$\begin{array}{c} {\large{\text{Osservo: }}} a_{n}+|a_{n}| \geq 0 \qquad (\forall x \in \mathbb{R} x+|x|\geq 0) \\{\large{\text{Inoltre: }}} a_{n}+|a_{n}| \leq 2|a_{n}| \qquad (\forall x \in \mathbb{R} x+|x|\leq 2|x|) \end{array}$$
Per il [[Criterio del confronto di serie]]:
$$0 \leq a_{n} +|a_{n}|\leq 2{\color{orange}|a_{n}|}$$
${\color{orange}\sum^{+\infty}_{n=0} 2|a_{n}| \text{ converge per ipotesi}}\qquad \longrightarrow \qquad {\color{Red}\sum^{+\infty}_{n=0}(a_{n}+|a_{n}|) \text{ converge}}$
$$$$ Quindi:
$$\sum^{+\infty}_{n=0} a_{n}={\color{Red}\underbrace{\sum^{+\infty}_{n=0} (a_{n}+|a_{n}|)}_{Converge}}-\color{orange}\underbrace{\sum^{+\infty}_{n=0} |a_{n}|}_{\text{converge per HP}}$$
$$\Longrightarrow\large\sum^{+\infty}_{n=0} a_{n} \text{ Converge}$$
Convergenza assoluta $\Longrightarrow$ Convergenza semplice