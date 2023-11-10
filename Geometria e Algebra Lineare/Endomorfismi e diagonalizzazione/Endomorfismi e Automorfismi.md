
#### Definizione
Dato $V$ uno [[Spazi vettoriali|spazio vettoriale]], un'[[Applicazioni lineari|applicazione lineare]] $f \in \mathrm{Hom}(V,V)$ si dice endomorfismo di $V$. L'insieme degli endomorfismi  di $V$ si indica con $\mathrm{End}(V)$. Un endomorfismo che sia anche isomorfismo si dice automorfismo di $V$ ed indichiamo con $\mathrm{GL}(V)$ l'insieme di tutti gli automorfismi di $V$.

Nello spazio $\mathrm{End}(V)$ abbiamo una seconda operazione oltre alla somma, ovvero la composizione di due applicazioni lineari. Questo ci permette di definire l'elevazione ad una potenza naturale di una applicazione e quindi il concetto di polinomio di applicazione

>[!info] Ossevazioni
> $\circ$ è interna ad $\mathrm{End}(v) : f,g \in \mathrm{End}(v) \to f \circ g \in \mathrm{End}(v)$
> $$f^{k} = \begin{cases}
> f \circ \dots \circ f  & \text{k volte se } k \in \mathbb{N}^{*} \to f^{k} \in end(v) \\ \\
> Id_{v} & \text{se } k =0
> \end{cases}$$
> $$P(f) = \sum^{k}_{i=0} c_{i} \cdot f^{i} = c_{0} \cdot Id_{v} + c_{1} \cdot f + \dots + c_{k} \cdot f^{k} \in \mathrm{End}(v)$$
> 
> Se $B$ è base di $V$, si denota $[f]_{BB} =[f]_{B}$ e $\varnothing_{BB} = \varnothing_{B}$
> 
> Si dice isomorfismo di gruppi:
> $$\varnothing_{B}:GL(V) \to GL(n;\mathbb{K})$ dove $n=\dim(V)$$ 
> $$\varnothing_{B}(f \circ g) = \varnothing_{B}(f) * \varnothing_{B}(g) \to \varnothing_{B}(p(f)) = p([f]_{B}) = \sum^{k}_{i=0} c_{i} \cdot [f]_{B}^{i}$$

