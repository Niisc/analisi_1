#lezione12 
![[Serie#Criterio del rapporto di Serie Criterio del rapporto]]

#### Dimostrazione
$$b = \lim_{ n \to +\infty } \frac{a_{n+1}}{a_{n}}$$
Se $b >1$ il termine generale $a_{n} \ \underline{non}$ tende a zero, non vale la [[Condizione necessaria per la convergenza]], la serie diverge.

se $b < 1$ esiste $q \in \mathbb{R} \quad b<q<1$
$$\forall \varepsilon > 0 \quad \exists n_{1} \in \mathbb{N} : \forall n \geq n_{1} \quad {\biggl|}\frac{a_{n+1}}{a_{n}} -b{\biggl|} < \varepsilon$$
$$\forall n \geq n_{1}= N \quad b - \varepsilon < \frac{a_{n+1}}{a_{n}} < b+\varepsilon < q + \varepsilon$$
$$ \begin{array} 
\ \text{si ha:} \quad a_{N+1}<(a+\varepsilon)a_{N}  \\
\ a_{N+2}<(a+\varepsilon)a_{N+1} < (a+ \varepsilon)^{2}a_{N} \\
\ a_{N+3}<(a+\varepsilon)a_{N+2} < (a+ \varepsilon)^{3}a_{N}  \\
\ \dots \\
\ a_{n}<(a+\varepsilon)^{n-N}a_{N} 
\end{array}$$ 

Per $\varepsilon$ "piccolo" suppongo $(q+\varepsilon) <1$
Per il [[Criterio del confronto di serie]]:
$$(a_{n}) < (a+\varepsilon)^{n-N}a_{n}=b_{n} \quad \text{con} \quad b_{n} \geq 0$$
Ora la serie:
$$\sum^{\infty}_{n=0} b_{n} = \sum^{\infty}_{n=0} (a+\varepsilon)^{n-N}a_{n}= \frac{a_{N}}{a+\varepsilon}^{N} \cdot \sum^{\infty}_{n=0} (a+\varepsilon)^{n}$$
È una [[Serie Geometrica]] di ragione $(q + \varepsilon)<1 \rightarrow$ convergente

Quindi anche la serie:
$$\sum^{\infty}_{n=0} a_{n}$$
Converge