#lezione6
### Definizione 
Una funzione è una terna (A,B,$f$) dove A,B sono insieme e $f$ è la legge che associa ad ogni elemento do A uno e un solo elemento di B
$A \rightarrow$ Dominio $\qquad B \rightarrow Codominio$
$$f:A \longrightarrow B$$
$$a\in A \quad f(a)\in B \ \mathrm{Immagine}$$
$$a\mapsto f(a) $$
$$\mathrm{Im}(f)=\{y \in B\  |\  \exists a \in A \ |\ f(a)=y\}\subseteq B \ Insieme \ delle \ immagini$$
#### Osservazione:
$Im(f) \not= \Gamma(f)$ 
Non confondere $Im(f)$ con $\Gamma (f)$ (grafico sottoinsieme del prodotto cartesiano di A e B):
$\Gamma(f)=\{(a,b)\in A\times B:a \in A\  \wedge\  b=f(a) \}$ 
[[Successioni]]
$$an= \mathbb{N} \longrightarrow \mathbb{R}$$
## Funzioni reali di variabile reale
$f: A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$
Esempio:
$f(x)=\sqrt{ x } \quad A= \mathbb{R}$ Non è una funzione
$f(x)=\sqrt{ x } \quad A=[0;+\infty)$ **è una funzione**
$Im(f)=\{y \in \mathbb{R} \ : \exists x\in [0;+\infty):f(x=y)\}=[0;+\infty)$$\Gamma(f)=\{(x,y)\in A\times \mathbb{R}:x \in [0;+\infty)\  :\  y=f(x)\}$ (grafico)

### Dominio naturale
si definisce dominio naturale l'insieme dei valori reali che rendono la funzione f con significato 
$\mathbb{D}_{f}=Dominio$
Esempio: $f(x)=\log(x+1)\qquad \mathbb{D}_{f}=\{x \in \mathbb{R}\ |\ x+1>0\}=(-1;+\infty)$
Data $f:A \longrightarrow B$ Funzione, $\mathrm{Im}(f) \subseteq B \subseteq \mathbb{R}$
## Funzioni limitate
$f$ si dice **Limitata** se è limitato l'insieme ([[Insiemi numerici limitati]])  $Im(f)$ ovvero se esiste $M>0$ tale che:
$$\forall y \in Im(f) \quad -M \le y \le M $$	$$f(x)=y \quad -M \le y \le M\quad   \forall x \in \mathbb{D}_f$$
### Funzioni limitate superiormente
$f$ si dice **Limitata superiormente** se è limitato superiormente l'insieme ([[Insiemi numerici limitati]])  $Im(f)$ ovvero se esiste $k \in \mathbb{R}$  tale che:
$$\forall y \in Im(f) \quad y \le k $$
$$f(x)\le k \quad \forall x \in \mathbb{D}_f$$
### Funzioni limitate inferiormente
$f$ si dice **Limitata inferiormente** se è limitato inferiormente l'insieme ([[Insiemi numerici limitati]])  $Im(f)$ ovvero se esiste $k \in \mathbb{R}$  tale che:
$$\forall y \in Im(f) \quad k \le y $$
$$k\le f(x) \quad \forall x \in \mathbb{D}_f$$
## Tipi di Funzione

### Crescente
$f$ si dice Crescente in $I \subseteq \mathbb{D}_f$ (I intervallo) se $\forall x_1,x_2 \in I \quad x_1<x_2$ si ha $f(x_1) \le f(x_2)$
#### Strettamente Crescente
$f$ si dice Strettamente Crescente se è crescente e $f(x_1)<f(x_2)$
### Decrescente
$f$ si dice Decrescente in $I \subseteq \mathbb{D}_f$ (I intervallo) se $\forall x_1,x_2 \in I \quad x_1<x_2$ si ha $f(x_2) \le f(x_1)$
#### Strettamente Decrescente
$f$ si dice Strettamente Decrescente se è decrescente e $f(x_2)<f(x_1)$

### Suriettiva
Sia $f:A \longrightarrow B$ 
$f$ si dice Suriettiva se $\forall y \in B \quad \exists a \in A : f(a)=y$ ovvero $Im(f)=$
#### Osservazioni
1) Data $f:A\longrightarrow B$ funzione, se considero la restrizione $\overline{f}:A\longrightarrow Im(f)$, $\overline{f}$ è suriettiva
2) Se $f$ è suriettiva, per ogni elemento del codominio esiste almeno un elemento del dominio che gli corrisponde mediante $f$
3) Se $f: A \subseteq \mathbb{R} \rightarrow B \subseteq \mathbb{R}$ $f$ suriettiva se considerando il fascio di rette $y=k \quad k \in B$, ogni retta interseca il grafico di $f$ in almeno un punto.
### Iniettiva
Sia $f:A \longrightarrow B$ 
$f$ si dice Iniettiva se $\forall x_1,x_2 \in A \quad  f(x_1)=f(x_2) \Longrightarrow x_1=x_2$
#### Osservazioni
1) Per ogni elemento del codominio esiste al massimo un elemento del dominio che gli corrisponde
2) se $f:A \subseteq \mathbb{R} \longrightarrow B \subseteq \mathbb{R}$ $f$ è iniettiva se considerando il fascio di rette $y=k\quad k\in B$, ogni retta interseca il grafico di $f$ in al massimo un punto.
### Biunivoca / Biettiva 
$f$ si dice Biunivoca o Biettiva se $f$ è iniettiva e suriettiva su A e B
#### Osservazione: Sia $f:A \subseteq \mathbb{R}\longrightarrow \mathbb{R}$ Iniettiva
$$\forall y \in Im(f)\quad \exists ! \ x \in A : f(x)=y$$

#finire 

### Inversa
Sia $f:A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$ una funzione iniettiva, si dice funzione inversa:
$$f^{-1}:Im(f)\longrightarrow \mathbb{D}_f$$
Definita da $\forall y \in Im(f) \quad f^{-1}(y)=x \iff f(x)=y$ 
#### Proprietà
- $\mathbb{D}_{f^{-1}}=Im(f) \qquad \mathbb{D}_f = Im(f^{-1})$ 
- $f^{-1}: Im(f)\longrightarrow \mathbb{D}_f$ è iniettiva e suriettiva
- Il grafico di $f^{-1}$ si ottiene dal grafico di $f$ operando  con una simmetria rispetto alla bisettrice del I- III quadrante
### Monotona
Sia $f: A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$ una funzione, si dice monotona in $I \subseteq A$ se $f$ è crescente (o decrescente) in $I$
#### Osservazione 
Sia $f:A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$ funzione monotona, allora è iniettiva, quindi sì piò definire $f^{-1}: Im(f)\longrightarrow A$ ![[photo1697212805.jpeg]]
### Pari
Sì dice che $f:A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$ è pari se A è un dominio simmetrico rispetto all'origine e se $\forall x \in A$
$f(x)=-f(x)$
#### Osservazione: se f è pari, $\Gamma(f)$$ è simmetrico all'asse y
### Dispari
Sì dice che $f:A \subseteq \mathbb{R} \longrightarrow \mathbb{R}$ è dispari se A è un dominio simmetrico rispetto all'origine e se $\forall x \in A$
$f(x)=-f(-x)$
#### Osservazione: se f è dispari, $\Gamma(f)$$ è simmetrico all'origine 
### Periodica
$f$  sì dice   periodica di periodo T se $\forall x \in \mathbb{D}_{f} \quad x+T\in \mathbb{D}_{f} \quad f(x)=f(x+T)$

# Funzioni elementari
![[photo1697212805 (1).jpeg]]
![[photo1697212805 (2).jpeg]]
![[photo1697212805 (3).jpeg]]