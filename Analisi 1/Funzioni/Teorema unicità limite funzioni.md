#lezione14

Sia $f:A \subseteq \mathbb{R} \to \mathbb{R}$ Una funzione e sia $x_{0}$ un punto di accumulazione per $A$. Se $\lim_{ x \to x_{0} } f(x) = l_{1}$ e $\lim_{ x \to x_{0} } f(x) = l_{2}$, allora $l_{1}=l_{2}$

> [!tip] In parole povere
> È simile a quello precedentemente definito per le successioni in [[Teorema di unicità del limite (Successioni)]]
#### Dimostrazione
Per assurdo $$l_{1} \neq l_{2} \quad l_{1}  > l_{2}$$
Dato che
$$\lim_{ x \to x_{0} } f(x) = l_{1}$$
si ha che
$$\forall \varepsilon > 0 \quad \exists \delta_{1} : \forall x \in (x_{0} - \delta_{1} ; x_{0}+\delta_{1}) \setminus \{x_{0}\}$$
$$|f(x) - l_{1}| <\varepsilon \quad \longrightarrow \quad l_{1} - \varepsilon   < f(x) < l_{1} + \varepsilon$$

Lo stesso ragionamento si può fare può fare per $l_{2}$

Dato che
$$\lim_{ x \to x_{0} } f(x) = l_{2}$$
si ha che:
$$\forall \varepsilon > 0 \quad \exists \delta_{2} : \forall x \in (x_{0}- \delta_{2}; x_{0} + \delta_{2}) \setminus \{x_{0}\}$$
si ha 
$$|f(x) - l_{2}| < \varepsilon \quad \longrightarrow \quad l_{2} - \varepsilon < f(x) < l_{2} + \varepsilon$$
Considero gli intervalli:
$$(l_{1}-\varepsilon;l_{1}+\varepsilon)$$
$$(l_{2}-\varepsilon; l_{2}+\varepsilon)$$

Se scelgo $\varepsilon = \frac{{l_{1}-l_{2}}}{2}>0$
$$(l_{1}-\varepsilon;l_{1}+\varepsilon) = \left( \frac{{l_{1}+l_{2}}}{2};\frac{3l_{1}-l_{2}}{2} \right)$$
$$(l_{2} - \varepsilon ; l_{2} + \varepsilon) = \left( \frac{{3l_{2}-l_{1}}}{2}; \frac{l_{1} + l_{2}}{2} \right)$$
$\left( \frac{{l_{1}+l_{2}}}{2};\frac{3l_{1}-l_{2}}{2} \right)$ e $\left( \frac{{3l_{2}-l_{1}}}{2}; \frac{l_{1} + l_{2}}{2} \right)$ non si intersecano

 si ha $(l_{1} - \varepsilon; l_{1} + \varepsilon) \cap(l_{2}-\varepsilon;l_{2}+\varepsilon) = \varnothing$
 
 sia $\delta = \min(\delta_{1}, \delta_{2}): \forall x \in (x_{0}-\delta;x_{0}+\delta) \setminus \{x_{0}\}$
 
 si ha che:
$$l_{1} - \varepsilon < f(x) < l_{1} + \varepsilon$$
$$l_{2} - \varepsilon < f(x) < l_{2} +\varepsilon$$
quindi $f(x) \in (l_{1} - \varepsilon; l_{1}+ \varepsilon) \cap(l_{2}-\varepsilon;l_{2}-\varepsilon) = \varnothing$

È un assurdo. Quindi $l_{1}=l_{2}$

>[!Exercise] Esercizio
Mostrare che $\lim_{ x \to 0 } \sin\left( \frac{1}{x} \right)$ non esiste con le funzioni.
