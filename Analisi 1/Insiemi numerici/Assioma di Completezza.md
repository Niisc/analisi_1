>[!tip] In parole povere
>  L'assioma di completezza, detto anche assioma di continuità, stabilisce che i numeri reali si susseguono con continuità, ossia che l'insieme $\mathbb{R}$ dei [[Numeri reali]] è "privo di buchi".
#### Dimostrazione
Siano $A,B \subseteq \mathbb{R}$ tali che $A,B \neq \emptyset$ e
1) $A \cap B = \emptyset$ e $A \cup B = \mathbb{R}$
2) $\forall a \in A \ \wedge \ \forall b \in B \quad a < b$

Allora esiste un *unico* $s \in \mathbb{R}$ tale che:
$$a \leq s < b \quad a < s \leq b \quad \forall a \in A \quad \forall b \in B$$
![[Assioma di Completezza 2023-11-04 18.06.58.excalidraw]]

>[!info] Osservazione
> In $\mathbb{Q}$ non vale l'assioma di completezza
> $$B = \{ x \in \mathbb{Q}: x \geq 0 \quad x^{2} \geq 2 \}$$
> $$A = \{ x \in \mathbb{Q} : x \geq 0 \quad x^{2} < 2 \ \vee \ x <0 \}$$
> $$s = \sqrt{ 2 } \not \in \mathbb{Q}$$

$\mathbb{R}$ è un campo ordinato completo