![[Serie#1) Serie Armonica]]
#### Dimostrazione
$$a_{n}=\frac{1}{n}>0\qquad \forall n\geq 1$$
$$\lim_{ n \to +\infty } \frac{1}{n}=0 \color{orange}$$
(Vale la [[Condizione necessaria per la convergenza]])
Considero $b_{k}=\left( 1+\frac{1}{k} \right)^{k}\quad k\in \mathbb{N} \quad k \geq 1$
Sappiamo che $\forall k \geq k_{0}\quad b_{k}\leq e$
Calcolo il logaritmo $log$:
$$\log(b_{k})=\log\left(1+ \frac{1}{k}\right)^{k}\leq \log(e)=1$$
$$k\cdot \log\left(1+ \frac{1}{k}\right)\leq 1$$
$$\log\left(1+ \frac{1}{k}\right)\leq \frac{1}{k}$$
$$\log\left(\frac{k+1}{k}\right)\leq \frac{1}{k}$$$$\underbrace{\log(k+1)-\log(k)}_{c_{k}}\leq \frac{1}{k}\qquad c_{k}\leq a_{k}=\frac{1}{k}$$
Considero la **Somma parziale**:
  
$$\sum^{p}_{k=0} c_{k}=\sum^{p}_{k=1} \log(k+1)-\log(k)$$$$[\log(p+1)-\cancel{\log (p)}]+[\cancel{\log(p)}-\cancel{\log(p-1)}]+[\cancel{\log(p-1)}-\log (p-2)]+\dots$$$$\dots+[\log(2)-\log (1)]=[\log(p+1)-\log(1)]=\log(p+1)$$
##### La successione delle somme parziali di $c_{k}$ è 
$S_{p}=\{\log(p+1)\}$
Per il criterio del confronto, dato che $c_{k} \leq a_{k}$ si ha che: $$S_{p}\leq T_{p}\quad dove:\quad T_{p}=\sum^p_{n=1} a_{k}$$
Calcolo il limite: 
$$\lim_{ p \to +\infty }S_{p}=\lim_{ p \to +\infty }\log(p+1)=+\infty$$
$$\Longrightarrow\lim_{ p \to +\infty }T_{p}=+\infty \quad \text{ovvero} \quad \sum^{\infty}_{n=1} \frac{1}{n} \Rightarrow \text{Diverge}$$ 