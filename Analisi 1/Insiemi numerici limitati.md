#lezione3 
### Intervalli
##### Intervalli limitati
Dati $a,b\in \mathbb{R}$, si definisce *intervallo* di estremi a e b uno dei seguenti insiemi:
$(a,b)=\{x\in R| a<x<b\}$ $\rightarrow$ Intervalli **limitati** **CHIUSI**
$[a,b]=\{x\in R| a\leq x \leq b\}$ $\rightarrow$ Intervalli **limitati APERTI**
$[a,b)=\{x\in R| a\leq x < b\}$ $\rightarrow$ Intervalli limitati
$(a,b]=\{x\in R| a< x \leq b\}$ $\rightarrow$ Intervalli limitati

##### Intervalli illimitati
$(-\infty; a) = \{x\in R| x < a\}$
$(-\infty; a]=\{x\in R| x \leq a\}$
$(a; +\infty)=\{x\in R| x < a\}$
$[a; +\infty)=\{x\in R| x \leq a\}$
### Intorno
Sia $x_0 \subset R$, definisco **intorno** di $x_0$ di raggio $\delta>0$ :$$(x_0-\delta;x_0+\delta)=\{x\in R \quad:\quad |x-x_0|<\delta\}$$
### Estremi
Sia $E\subseteq R$  un insieme numerico: 
E si dice **Limitato** se esistono due numeri $m,M\in R$ tali che:$$\forall x \in E \qquad m\leq x \leq M$$
E si dice **Superiormente Limitato** se esiste un numero $M\in R$ tale che:$$\forall x \in E \qquad x \leq M$$
E si dice **Inferiormente Limitato** se esiste un numero $m\in R$ tale che:$$\forall x \in E \qquad m\leq x$$
### Massimo e Minimo
$\bar x\in \mathbb{R}$ è massimo per $E$ se
$\bar x\in E$ , $\forall x\in E \qquad x\leq \bar x$  

$\tilde x\in \mathbb{R}$ è minimo per $E$ se
$\tilde x\in E$ , $\forall x\in E \qquad \tilde x \leq x$  

Anche se $E$ è limitato non è detto che abbia massimo o minimo:
$E=N \rightarrow \min(E)=0$ , Non esiste massimo

### Maggiorante e Minorante
$a \in \mathbb{R}$ si dice **Maggiorante** per $E$ se: $$\forall x\in E\qquad x\leq a$$
$b \in \mathbb{R}$ si dice **Minorante** per $E$ se: $$\forall x \in E \qquad b\leq x$$
Non è detto che $a\in E$ o $b\in E$ 
Se E è superiormente/inferiormente limitato, E ha maggioranti(minoranti)
Dato un maggiorante ne posso costruire infiniti altri
#### Estremi Superiore e Inferiore
Si dice **Estremo Superiore** di E sup(E) il minimo dei maggioranti di E
a=$Sup(E)$ se a è maggiorante $\forall \in E \quad x\leq a$
Si dice Estremo Inferiore di E Inf(E) il massimo dei minoranti E:
b=$Inf(E)$ se a è minorante $\forall \in E \quad b \leq x$ 
### Teorema: Ogni insieme $E \subseteq R$ non vuoto e limitato superiormente(inferiormente) ammette un estremo superiore(inferiore). 
#lezione4
##### Dimostrazione
Sia $E \subseteq R\qquad E\not= \emptyset$ limitato superiormente
$\Longrightarrow$ $E$ ammette maggioranti
chiamo $M$ l'insieme dei maggioranti per $E$: $$M=\{x \in R\ |\ \forall e \in E \quad e \leq x\}$$ Osservo $M \not=$ 0 (esiste almeno un maggiorante)
$M$ è limitato inferiormente $$e\in E \quad \forall x \in M\quad e\leq x$$
considero l'insieme P=