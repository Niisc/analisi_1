#lezione3 
## Intervalli
#### Intervalli limitati
Dati $a,b\in \mathbb{R}$, si definisce *intervallo* di estremi a e b uno dei seguenti insiemi:
$(a,b)=\{x\in \mathbb{R}| a<x<b\}$ $\rightarrow$ Intervalli **limitati** **CHIUSI**
$[a,b]=\{x\in \mathbb{R}| a\leq x \leq b\}$ $\rightarrow$ Intervalli **limitati APERTI**
$[a,b)=\{x\in \mathbb{R}| a\leq x < b\}$ $\rightarrow$ Intervalli limitati
$(a,b]=\{x\in \mathbb{R}| a< x \leq b\}$ $\rightarrow$ Intervalli limitati

#### Intervalli illimitati
$(-\infty; a) = \{x\in \mathbb{R}| x < a\}$
$(-\infty; a]=\{x\in \mathbb{R}| x \leq a\}$
$(a; +\infty)=\{x\in \mathbb{R}| x < a\}$
$[a; +\infty)=\{x\in \mathbb{R}| x \leq a\}$
## Intorno
Sia $x_0 \subset \mathbb{R}$, definisco **intorno** di $x_0$ di raggio $\delta>0$ :$$(x_0-\delta;x_0+\delta)=\{x\in \mathbb{R} \quad:\quad |x-x_0|<\delta\}$$
## Estremi
Sia $E\subseteq R$  un insieme numerico: 
E si dice **Limitato** se esistono due numeri $m,M\in \mathbb{R}$ tali che:$$\forall x \in E \qquad m\leq x \leq M$$
E si dice **Superiormente Limitato** se esiste un numero $M\in \mathbb{R}$ tale che:$$\forall x \in E \qquad x \leq M$$
E si dice **Inferiormente Limitato** se esiste un numero $m\in \mathbb{R}$ tale che:$$\forall x \in E \qquad m\leq x$$
## Massimo e Minimo
$\bar x\in \mathbb{R}$ è massimo per $E$ se
$\bar x\in E$ , $\forall x\in E \qquad x\leq \bar x$  

$\tilde x\in \mathbb{R}$ è minimo per $E$ se
$\tilde x\in E$ , $\forall x\in E \qquad \tilde x \leq x$  

Anche se $E$ è limitato non è detto che abbia massimo o minimo:
$E=N \rightarrow \min(E)=0$ , Non esiste massimo

## Maggiorante e Minorante
$a \in \mathbb{R}$ si dice **Maggiorante** per $E$ se: $$\forall x\in E\qquad x\leq a$$
$b \in \mathbb{R}$ si dice **Minorante** per $E$ se: $$\forall x \in E \qquad b\leq x$$
Non è detto che $a\in E$ o $b\in E$ 
Se E è superiormente/inferiormente limitato, E ha maggioranti(minoranti)
Dato un maggiorante ne posso costruire infiniti altri
### Estremi Superiore e Inferiore
Si dice **Estremo Superiore** di E sup(E) il minimo dei maggioranti di E
a=$\sup(E)$ se a è maggiorante $\forall \in E \quad x\leq a$
Si dice Estremo Inferiore di E Inf(E) il massimo dei minoranti E:
b=$\inf(E)$ se a è minorante $\forall \in E \quad b \leq x$ 

### [[Teorema di esistenza degli estremi superiori e (o) inferiori]]
![[Teorema di esistenza degli estremi superiori e (o) inferiori#Ipotesi]]