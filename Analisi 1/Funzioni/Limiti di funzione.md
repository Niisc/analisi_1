#lezione13
### Definizione (finito al finito)
Sia $f:A \subseteq \mathbb{R} \to \mathbb{R}$ [[Funzioni|funzione]]. Sia $x_{0}$ un [[punto di accumulazione]] per $A$. Diciamo che $f$ ha limite $l \in \mathbb{R}$ per $x$ che tende a $x_{0}$ e scriviamo 
$$\lim_{ x \to x_{0} } f( x)=l$$
se:
$$\large\boxed{\begin{array}
\ \forall \varepsilon > 0 \quad \exists \delta = \delta(\varepsilon) >0 \quad \text{tale che} \\
 \forall x \in (x_{0} - \delta; x_{0}+ \delta) - \{x_{0}\} \cap A \quad \text{si ha} \\
{\color{orange}|f(x)-l| < \varepsilon}
\end{array}}$$

>[!info]
>- Il valore di f in $x_{0}$ non conta: $f$ in $x_{0}$ può anche non essere definita
>- $\delta=\delta(\varepsilon)$ rappresenta la "distanza" di $x$ dal punto $x_{0}$
>- $\varepsilon$ rappresenta la "distanza" di $f(x)$ da $l$

>[!example] Esempio
> 	$$f(x) = \sqrt{ x-1 } \quad \mathbb{D}_{f} = [1; + \infty)$$
> 	verifico con la definizione che $\lim_{ n \to 7 } \sqrt{ x-1 } = \sqrt{ 6 }$
> si ha:
>  $$|\sqrt{ x-1 }-\sqrt{ 6 }| < \varepsilon$$
$$-\varepsilon < \sqrt{ x-1 } < \varepsilon$$
$$\sqrt{ 6 }-\varepsilon < \sqrt{ x-1 } < \varepsilon + \sqrt{ 6 }$$
Intorno al quadrato
$$(\sqrt{ 6 }-\varepsilon)^{2} < x-1<(\varepsilon+\sqrt{ 6 })^{2}$$
$$(\sqrt{ 6 }-\varepsilon)^{2}+1 < x<(\sqrt{ 6 }+\varepsilon)^{2} +1$$
$$7-2\varepsilon \sqrt{ 6 }+ \varepsilon^{2} < x< 7 + 2\varepsilon \sqrt{ 6 } \varepsilon ^{2}$$
$$\delta_{1} = 7-(7 - + \varepsilon^{2} - 2 \varepsilon \sqrt{ 6 }) \quad \delta_{2} = 7 + \varepsilon^{2} + 2\varepsilon \sqrt{ 6 }-7$$
> Scelgo il minimo $\delta = \min(\delta_{1},\delta_{2}): \forall x \in (7 - \delta ; 7+ \delta) - \{7\}$
> $$|\sqrt{ x-1 }-\sqrt{ 6 }| < \varepsilon$$


> [!example] Esempio
> $$f(x) = x^{2} \quad \mathbb{D}_{f} = \mathbb{R}$$
> Verifico con la definizione  che $\lim_{ x \to 2 } x^{2} \neq 5$
> 
> > [!attention] **Se** fosse vero
> $$\forall \varepsilon > 0 \quad \exists \delta=\delta(\varepsilon) > 0 : \forall x \in (2-\delta ; 2+ \delta) - \{2\}$$
> si ha $|x^{2} - 5| < \varepsilon$
> $$5 - \varepsilon < x^{2} < \varepsilon + 5$$
Estraggo la radice quadrata $\sqrt{ 5-\varepsilon } < x < \sqrt{ 5 + \varepsilon }$
 $$\underbrace{ \sqrt{ 5- \varepsilon } < 2 }_{ 5- \varepsilon < 4 \quad \text{questa relazione è solo vera se } \varepsilon > 1 \text{ quindi non vale } \forall \varepsilon } < \sqrt{ 5 + \varepsilon }$$
(invece $2< \sqrt{ 5 + \varepsilon }$ vale sempre. Ricordati che $\varepsilon > 0$)
Quindi non esiste $\delta(\varepsilon) : |x^{2} - 5| < \varepsilon$


> [!example] Esempio
> $$f(x) = \lfloor x \rfloor \quad \mathbb{D}_{f}=\mathbb{R}$$
> $$x_{0} = 2 \quad f(x)= 1 \quad 1 \leq x < 2$$
$$ f(x) = 2 \quad 2 \leq x < 3$$
Verifico che il limite per $x \to 2$ non esiste per assurdo suppongo che $\lim_{ x \to 2 } f(x) = l$
$$\forall \varepsilon > 0 \quad \exists \delta = \delta ( \varepsilon) > 0 : \forall x \in (2 - \delta; 2+ \delta) - \{2\} \cap \mathbb{D}_{f}$$
si ha $|f(x) - l| < \varepsilon$
>$$I_{\delta}(2) = \begin{cases}
> \text{per} & x> 2 & f(x) = 2 \rightarrow |2-l| < \varepsilon \\
> \text{per} & x < 2 & f(x) = 1 \rightarrow |1-l| < \varepsilon   
>\end{cases}$$
$$\varepsilon > | 2 -l| = |1 + 1- l| \geq 1 - |1-l| > 1 - \varepsilon$$
$$\rightarrow 2 \varepsilon > 1 \quad \varepsilon > \frac{1}{2}  \text{ e quindi non vale } \forall \varepsilon > 0$$
**Assurdo** quindi $l$ non eisiste

# lezione 15
#finire non so come ha fatto la prof a lezione

### Definizione (+infinito al finito)

Sia $f:A \subseteq \mathbb{R} \to \mathbb{R}$ [[Funzioni|funzione]]. Sia $x_{0}$ un [[punto di accumulazione]] per $A$. Diciamo che $f$ ha limite $l \in \mathbb{R}$ per $x$ che tende a + infinito ($+\infty$) e scriviamo 
$$ \lim_{ x \to +\infty} f( x)=l  $$
se:
$$\large\boxed{\begin{array}
\ \forall \mathcal{M} > 0 \quad \exists \delta = \delta(\varepsilon) >0 \quad \text{tale che} \\
 \forall x \in (x_{0} - \delta; x_{0}+ \delta) - \{x_{0}\} \cap A \quad \text{si ha} \\
{\color{orange}f(x) > \mathcal{M}}
\end{array}}$$
### Definizione (-infinito al finito)

Sia $f:A \subseteq \mathbb{R} \to \mathbb{R}$ [[Funzioni|funzione]]. Sia $x_{0}$ un [[punto di accumulazione]] per $A$. Diciamo che $f$ ha limite $l \in \mathbb{R}$ per $x$ che tende a - infinito ($-\infty$) e scriviamo 
$$ \lim_{ x \to -\infty} f( x)=l  $$
se:
$$\large\boxed{\begin{array}
\ \forall \mathcal{M} > 0 \quad \exists \delta = \delta(\varepsilon) >0 \quad \text{tale che} \\
 \forall x \in (x_{0} - \delta; x_{0}+ \delta) - \{x_{0}\} \cap A \quad \text{si ha} \\
{\color{orange}f(x) < -\mathcal{M}}
\end{array}}$$