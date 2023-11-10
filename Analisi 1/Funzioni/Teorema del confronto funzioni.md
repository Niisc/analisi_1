Siano $f,g,h$ funzioni definite da $A \subseteq \mathbb{R}$ e sia $x_{n}$ un punto di accumulazione per $A$.

Se esiste $\delta>0$ tale che $\forall x \in(x_{0} - \delta; x_{0}+\delta) \setminus \{ x_{0} \} \cap A$ si abbia $f(x) \leq g(x) \leq h(x)$ e se esistono:
$$\lim_{ x \to x_{0} } f(x)=\lim_{ x \to x_{0} } h(x)=l$$Allora:
$$\lim_{ x \to x_{0} } g(x)=l$$
>[!example] Esempio
> $$\lim_{ x \to 0 } \sin(x)=0$$
> Per:
> $$x_{0}=0 \quad x\in\left( -\frac{\pi}{2};\frac{\pi}{2} \right) \quad|\sin(x)| \leq|x|$$
> $$-x \leq \sin(x) \leq x$$
> Per il teorema del confronto:
> $$\lim_{ x \to 0 } (-x)=\lim_{ x \to \infty } (x) =0 \to \lim_{ x \to \infty } \sin(x)=0$$
> 
