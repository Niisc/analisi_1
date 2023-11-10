#lezione4 
#### Ipotesi:
Ogni insieme $E \subseteq R$ non vuoto e limitato superiormente (inferiormente) ammette un estremo superiore(inferiore)
#### Dimostrazione
Sia $E \subseteq R\quad E\not= \emptyset$ limitato superiormente $\Longrightarrow$ $E$ ammette maggioranti.

Chiamo $M$ l'insieme dei maggioranti per $E$: $$M=\{x \in \mathbb{R} |\ \forall e \in E \quad x \geq e\}$$
>[!info] Osservazione
Se $M \neq \emptyset$ (esiste almeno un maggiorante)
$M$ è limitato inferiormente 
$$e\in E \quad \forall x \in M \quad e\leq x$$

Definisco $N = \mathbb{R} \setminus M$

>[!info] Osservazione
> $N \neq \emptyset$ e per definizione:
> $$ M \cup N = \mathbb{R} \quad M \cap N = \emptyset$$
 
![[Insiemi numerici limitati 2023-11-04 17.40.38.excalidraw]]

Se $y \in N$, $y$ non è maggiorante per $E$
Esiste $e \in E$ tale che $y<e$
$$\forall y \in N \quad \forall x \in M \quad \underbrace{ y }_{ \color{orange} \text{non è maggiorante}  } < e < \underbrace{ x }_{ \color{green} \text{è maggiorante } }$$
Quindi $M$ e $N$ soddisfano le ipotesi dell'[[Assioma di Completezza|assioma di completezza]]: esiste $s \in \mathbb{R}$ unico tale che:
$$y < s \leq x \quad \forall y \in N$$
Oppure
$$y \leq s < x \quad \forall x \in M$$
Mostro che $s \in M$: s quindi è il minimo dei maggioranti$\longrightarrow s=sup(E)$
#finire 

Per assurdo $s \in N$: Allora esisterebbe un $\overline{e}\in E \ con: \quad \overline{e}>s \text{ (s non è maggiorante)}$

Ma allora costruisco $\huge \frac{s+\overline{e}}{2}$ tale che:
$$s<\frac{2+\overline{e}}{2}<\overline{e}\quad \Longrightarrow \frac{s+\overline{e}}{2}\in N \text{ non è maggiorante}$$ Quindi $\huge \frac{s+\overline{e}}{2}$ è l'elemento separatore

>[!warning] Assurdo
>Contro l'unicità dell'elemento separatore
