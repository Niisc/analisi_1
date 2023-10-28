##### Definizione
Una struttura algebrica è costituita da una collezione di [[insiemi]] $A_{1},\dots,A_{n}$, detti supporto della struttura ed una collezione di [[operazioni]] $*_{1},\dots,*_{m}$ su questi [[insiemi]]. Si indica con $(A_{1},\dots,A_{n}, *_{1},\dots,*_{m})$. Un omomorfismo è una [[Funzioni|funzione]] $f$ tra due strutture algebriche che preserva le loro [[operazioni]]. Se tale [[Funzioni|funzione]] è biunivoca e la funzione inversa $f^{-1}$ è a sua volta un omomorfismo, allora $f$ si dice isomorfismo e le due strutture si dicono ismorfe.

### Gruppo abeliano
##### Definizione
Sia $G$ un [[insiemi|insieme]] su cui è definita un'operazione interna $*$ soddisfacenti le seguenti tre proprietà:
1) esiste un elemento neutro $e\in G$ tale che $e*a=a*e=a \quad \forall a \in A$
2) per ogni $a \in G$ esiste l'elemento inverso $a^{-1} \in G$ tale che $a*a^{-1} = a^{-1}*a=e$
3) vale la proprietà associativa $(a*b)*c=a*(b*c)$ per ogni $a,b,c \in G$

Allora la struttura $(G,*)$ si dice gruppo. Se inoltre
4) Vale la proprietà commutativa $a*b=b*a$ per ogni $a,b \in G$

Allora $(G,*)$ è detto gruppo abeliano (o commutativo).

### Campo

##### Definizione
Sia $\mathbb{K}$ un [[insiemi|insieme]] su cui sono definite due operazioni interne $*, \circ$ tali che:
1) $(\mathbb{K}, *)$ è un [[Struttura algebrica#Gruppo abeliano|gruppo abeliano]] con elemento neutro $e$
2) definito $\mathbb{K}^{*} = \mathbb{K}\setminus \{e\}$ allora $(\mathbb{K}^{*}, \circ)$ è un [[Struttura algebrica#Gruppo abeliano|gruppo abeliano]]
3) vale la proprietà distributiva $a \circ (b *c)=(a \circ b)*(a \circ c)$ per ogni $a,b,c \in \mathbb{K}$

Allora la struttura $(\mathbb{K}, *, \circ)$ si dice campo.
