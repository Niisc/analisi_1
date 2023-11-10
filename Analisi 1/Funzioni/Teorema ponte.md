#lezione14
>[!tip] Suggerimento
> Il teorema ponte rende chiaro il legame tra teoria dei [[Limiti di funzione]] e [[Algebra dei limiti di successioni|limiti di successioni]].

Sia $f: A \subseteq \mathbb{R} \to \mathbb{R}$ una funzione e sia $x_{0}$ un [[Punto di accumulazione]] per $A$.
Allora: $\lim_{ x \to x_{0} } f(x) = l$  se e solo se per ogni [[Successioni|successione]] di [[numeri reali]] $\{x_{n}\}$ con $x_{n} \neq x_{0}$ che converge a $x_{0}$ si ha: $$\lim_{ n \to \infty } f(x_{n}) = l$$$$\boxed{\lim_{ x \to x_{0} } f(x)=l} \iff \boxed{\begin{array}
\ \forall x_{n} \text{ succesione reale } x_{n} \not= x_{0}  \text{ tale che:} \\
\lim_{ n \to +\infty }x_{n}=x_{0} \text{ si ha:} \\
\large \lim_{  n \to +\infty } f(x_{n})=l 
\end{array}}$$
>[!info] Osservazione
>$x_{n}$ successione reale $f(x_{n})$ successione delle immagini dei punti di $x_{n}$ tramite $f$

#### Dimostrazione
1) Se per ipotesi: ${\color{green}{\lim_{ x \to x_{0} } f(x) = l}} \Longrightarrow {\color{orange} \lim_{ n \to \infty } f(x_{n}) = l} \quad  \forall x_{n}$ successione tale che $\lim_{ n \to +\infty } x_{n} = x_{0}$ .

$${\color{green} \biggl[}\begin{array}{c}
\ \forall \varepsilon > 0 \quad \exists \delta = \delta(\varepsilon) > 0: \forall x \in (x_{0} - \delta;x_{0} + \delta) - \{x_{0}\} \cap A \\
\text{si ha:} \qquad |f(x) -l| = \varepsilon
\end{array}{\color{green}\biggl]}$$

Considero una [[Successioni|successione]] $x_{n}$ (non costante = $x_{0}$) che sia [[Successioni#Convergente|convergente]] a $x_{0}$ :
$$\color{red}\lim_{ n \to \infty } x_{n} = x_{0}$$
$${\color{red}\bigg[}\ \forall \bar{\varepsilon} > 0 \quad \exists n_{0} \in \mathbb{N} : \forall n \geq n_{0} \quad | x_{n} - x_{0}| < \bar{\varepsilon}{\color{Red}\bigg]}$$
$$-\bar{\varepsilon}<x_{n} - x_{0} < \bar{\varepsilon}$$
Scelgo $\delta = \bar{\varepsilon} :  \forall n \geq n_{0} \quad | x_{n}-x_{0}|< \bar{\varepsilon}$
$$-\delta <  x_{n} -x_{0} < \delta$$
Quindi:
$$x_{0}- \delta < x_{n} < x_{0} +\delta \Longrightarrow \color{green }{x_{n} \in (x_{0}-\delta;x_{0} + \delta)}$$
si ha $|f(x_{n})-l| < \varepsilon$

Riassunto:
$$ \forall \varepsilon > 0 \quad \exists n_{0} \in \mathbb{N}: \forall n \geq n_{0}\quad x_{n} \in (x_{0} - \delta;x_{0}+ \delta) \quad |f(x_{n})-l|<\varepsilon \longrightarrow \lim_{  n \to +\infty } f(x_{n})=l $$



2) Se per ipotesi: ${\color{orange}\lim_{ n \to +\infty } f(x_{n}) = l} \quad \forall x_{n} \text{ successione con } x_{n} \not= x_{0} :\lim_{ n \to +\infty } (x_{n}) =x_{0} \Longrightarrow {\color{green}\lim_{ x \to x_{0} } f(x) = l}$

Per assurdo non vale $\lim_{ x \to x_{0} } f(x) = l$
$\exists \varepsilon_{0} > 0 : \forall \delta > 0$ esiste un punto $x(\delta)$ tale che $|x(\delta) - x_{0}| < \delta$ ma $|f(x(\delta)) -l > \varepsilon_{0}$

Costruisco una successione che tende a $x_{0}$ ma per il quale $f(x_{n})$ $\underline{\text{non converge}}$ a $l$

porgo $x_n=x(\delta)$ con $\delta = \frac{1}{n} \quad \delta =1 ; \frac{1}{2} ; \frac{1}{3} ; \dots ; \frac{1}{n}$ ($\forall n \geq 1$)

poiché $|x(\delta) - x_{0}| < \delta \Rightarrow |x_{n} - x_{0}| <\frac{1}{n}=\delta$

questo è equivalente a dire la successione $x_{n}$ converge a $x_{0}$ 
$$\forall \varepsilon > 0 \quad \exists n = 1 \quad \forall n \geq 1 \quad | x_{n}- x_{0} | < \frac{1}{n} = \delta$$
Ma d’altra parte $|f(x(\delta)) - l | > \varepsilon_{0} \quad \forall \varepsilon_{0} > 0 : \forall n \geq 1 \quad |f(x_{n}) -l| > \varepsilon_{0}$ cioè:
$$\lim_{ n \to \infty } f(x_{n}) {\cancel{\color{Red}=}} l$$
Assurdo perché contro $\color{orange}l'ipotesi$
#finire mettere le foto 

> [!example] Esempio
> Mostrare che $\lim_{ x \to 0 } \sin\left( \frac{1}{x} \right)$ non esiste
> con le successioni
> per ogni successione $x_{n}$ che tende a $0=x_{0}$
> $$\lim_{ n \to \infty } f(x_{n}) = l$$
>- $$x_{n}=\frac{1}{x\pi n} \quad \lim_{ n \to \infty } \frac{1}{2 \pi n} = 0 = x_{0}$$
$$\lim_{ n \to \infty } f(x_{n}) = \lim_{ n \to \infty } f\left( \frac{1}{2 \pi n} \right) = \lim_{ n \to \infty } \sin(2 \pi n) = 0$$
>- $$x_{n = \frac{1}{\frac{\pi}{2} + 2 \pi n}} \quad \lim_{ n \to \infty } \frac{1}{\frac{\pi}{2} + 2\pi n} = 0 = x_{0}$$
$$\lim_{ n \to \infty } f(x_{n}) = \lim_{ n \to \infty } f\left( \frac{1}{\frac{\pi}{2}+ 2\pi n} \right) = \lim_{ n \to \infty } \sin\left( \frac{\pi}{2} + 2\pi n \right) = 1$$
Non è possibile che 
>$$\lim_{ n \to \infty } f(x_{n}) = \begin{cases}
0 \\
1 & 
\end{cases}$$
> Poiché è contro il [[Teorema di unicità del limite (Successioni)|Teorema di unicità del limite]] per successioni.
