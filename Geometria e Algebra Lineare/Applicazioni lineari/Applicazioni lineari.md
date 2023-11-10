Una applicazione lineare : $T:V \rightarrow W$ è una [[Funzioni|funzione]] tra due [[Spazi vettoriali|spazi vettoriali]] che gode delle seguenti proprietà:
$$T(v_{1} + v_{2})=T(v_{1})+T(v_{2}) \quad \forall v_{1}, v_{2} \in V$$
$$T(\lambda v)= \lambda T(v) \quad \forall v \in V, \lambda \in \mathbb{R}$$A ogni applicazione lineare può essere associata una [[matrici|matrice]] $A = M(T)$ che ha per colonne le immagini degli elementi della base di B, espresse rispetto alla base di $W$. Salvo indicazione le basi di $V$ e $W$ sono le basi canoniche. Usando la matrice associata.
$$T(V) = A \cdot v \quad \forall v \in V$$
Una applicazione lineare può essere definita tramite:

1) La regola
>[!example] Esempio
> $$T : \mathbb{R}^{2} \to \mathbb{R}^{3} \quad \text{tale che}$$
$$T(x,y)=(x+y,2x,x-y)$$

2) Le immagini di una base:
>[!example] Esempio
> $$T: \mathbb{R}^{2} \to \mathbb{R}^{3} \quad \text{tale che}$$
$$T(e_{1}) = (1,2,1)$$
$$T(e_{2})=(1,0,-1)$$

3) La matrice associata rispetto ad una base:
>[!example]  Esempio
> $$T: \mathbb{R}^{2} \to \mathbb{R}^{3} \quad \text{tale che la matrice associata rispetto alle basi canoniche è}$$
>$$A = \left[\begin{matrix}
> 1  & 1 \\
> 2  & 0  \\
> 1  & -1
> \end{matrix}\right]$$

Se non è specificato, la matrice si intended sempre associata alle basi canoniche.
Le tre precedenti definizioni definiti sono la stessa applicazione lineare.

## Immagine $\mathrm{Im}(T)$
L’immagine $\mathrm{Im}(T)$ di una applicazione lineare $T: V \to W$ è lo spazio generato dalle immagini degli elementi di una base $B=\{v_{1},v_{2},\dots, v_{n}\}$ di $V$:

$$\mathrm{Im}(T)=\{T(v)|v \in V\}=(T(v_{1}),\dots,T(v_{n})) \subseteq W$$
Utilizzando la matrice $A=M(T)$ associata:

1) $\mathrm{Im}(T)$ =  spazio generato dalle colonne di $A$
> [!attention] Attenzione
> Prestare attenzione se le basi di $V$ e $W$ non sono quelle canoniche.

2) $B(\mathrm{Im}(T)) = \{\text{colonne linearmente indipendenti di } A\}$
> [!attention] Attenzione
> Prestare attenzione se le basi di $V$ e $W$ non sono quelle canoniche.

3) $\dim(\mathrm{Im}(T))= \text{rg}(A)$

## Nucleo
Il nucleo $\ker(T)$ di una applicazione lineare $T: V \to W$ è il sotto spazio di $V$ formato dagli elementi la cui immagine è lo $0$:
$$\ker(T) = \{c\in V | T(v) = 0\} \subseteq V$$
Utilizzando la matrice $A$ associata:
- $\ker(T) = $