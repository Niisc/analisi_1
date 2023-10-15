### Definizione
una successione numerica è una legge che associa ad ogni numero naturale $n \in \mathbb{N}$ un unico numero reale.
$a_{n}: \mathbb{N} \rightarrow \mathbb{R}$ Funzione particolare
$n \rightarrow a_{n}$
##### Esempio
1) $a_{n}=n^{3}$
$\{a_{n}\}=\{0;1;8;27;\dots\}$

2) $a_{n}=\frac{1}{n-2}$ 
$\{a_{n}\}=\{\frac{-1}{2};-1;1;\frac{1}{2};\frac{1}{3};\dots\}$ 
Dal punto di grafico, ricordo che $a_{n}$ è un insieme *discreto*
![[Pasted image 20231015161026.png|500]]

#### Successione positiva/negativa definizione
La successione $a_{n}$ si dice positiva se $a_{n}\geq0 \quad \forall n \in \mathbb{N}$ e negativa se $a_{n}\leq 0 \quad \forall n \in \mathbb{N}$
La successione $a_{n}$ è definitivamente positiva se: 
$$\exists n_{0} \in \mathbb{N}: \quad \forall n \geq n_{0} \quad a_{n}\geq 0$$
#### Limitata superiormente
La successione $a_{n}$ si dice limitata superiormente se esiste $M \in \mathbb{R}$ tale che $\forall n \in \mathbb{N} \quad a_{n}\leq M$ 
#### Limitata inferiormente
La successione $a_{n}$ si dice limitata inferiormente se esiste $m \in \mathbb{R}$ tale che $\forall n \in \mathbb{N} \quad a_{n}\geq m$ 
#### Monotona crescente
La successione $a_{n}$ si dice monotona crescente se $\forall n \in \mathbb{N} \quad a_{n+1} \geq a_{n}$ 
#### Monotona decrescente
La successione $a_{n}$ si dice monotona decrescente se $\forall n \in \mathbb{N} \quad a_{n+1} \leq a_{n}$ 

##### Esempio
$\large a_{n}=\frac{1}{ n-2} \quad n\neq2$ 
1) Definitivamente positiva $\forall n \geq 3 \quad a_{n}=\frac{1}{n-2}\geq 0$ 
2) Limitata inferiormente $\forall n \in \mathbb{N} - \{2\} \quad a_{n}\geq -1$

Verifico che $a_{n}\geq -1$
$\frac{1}{n-2}\geq-1 \rightarrow \frac{1+n-2}{n-2}\geq0$
$\frac{n-1}{n-2}\geq0$
![[Pasted image 20231015164239.png|300]]

3) Limitata superiormente $\forall n \in \mathbb{N}-\{2\} \quad a_{n}\leq1$
Verifico che $a_{n}\leq 1$
$\frac{1}{n-2}\leq 1 \rightarrow \frac{1-n+2}{n-2}\leq0$
$\frac{3-n}{n-2}\leq 0$
![[Pasted image 20231015164458.png|300]]

4) Strettamente decrescente $\forall n \in \mathbb{N} - \{2\} \quad a_{n+1} < a_{n}$
Verifico che $a_{n+1}<a_{n}$
$\frac{1}{(n+1)-2}<\frac{1}{n-2}$
$\frac{1}{n-1}<\frac{1}{n-2}\rightarrow \frac{-1}{(n-1)(n-2)}<0$
con $(n-1)(n-2)$ positivo
#### Convergente
Una successione $a_{n}$ si dice convergente se esiste un [[Numeri reali|numero reale]] $l\in \mathbb{R}$ tale che:
$$\forall \varepsilon>0 \quad \exists n_{0} \in \mathbb{N} : \quad \forall n \geq n_{0}\quad |a_{n}-l| < \varepsilon$$
Si scrive $\lim_{n \to \infty}{a_{n}} =l$ 
##### Esempio
$a_{n}=\frac{n-2}{n} \quad \lim_{n \to \infty} a_{n}=1$
Verifico la definizione che $\lim_{n \to \infty} \frac{n-2}{n}=1$
$$\forall \varepsilon > 0 \quad \exists n_{0}\in \mathbb{N} : \quad \forall n\geq n_{0} \quad |\frac{n-2}{n}-1|<\varepsilon$$
$$|\frac{n-2}{n}-1|<\varepsilon \rightarrow |\frac{-2}{n}|<\varepsilon \rightarrow n > \frac{2}{\varepsilon}$$
$\forall \varepsilon >0$ costruisco $n_{0}$ tale che $\forall n\geq n_{0}$ si ha $|a_{n}-1|<\varepsilon$

#### Divergente a $+\infty$
Una successione $a_{n}$ è divergente a $+ \infty$ se:
$$\forall M > 0 \quad \exists \bar{n}\in\mathbb{N} :\quad \forall n \geq \bar{n} \quad a_{n} \geq M$$

#### Divergente a $-\infty$
Una successione $a_{n}$ è divergente a $- \infty$ se:
$$\forall M > 0 \quad \exists \bar{n}\in\mathbb{N} :\quad \forall n \geq \bar{n} \quad a_{n} \leq -M$$

##### Esempio
$\large a_{n}=e^{n} \quad \lim_{n \to \infty} a_{n}= + \infty$
Verifico con la definizione che $\lim_{n \to \infty} e^{n}= + \infty$
$$\forall M > 0 \quad \exists \bar{n} \in \mathbb{N} : \quad \forall n \geq \bar{n} \quad e^{n}\geq M \quad n\geq \ln(M)$$
Scelgo $\bar{n} = \lfloor \ln(M)\rfloor+1 > \ln(M)$
(Guarda [[Arrotondamento]] per parentesi strane)
$\forall M >0$ costruisco $\bar{n}$ tale che $\forall n \geq \bar{n}$ si ha $e^{n} \geq M$

##### Esempio
$\large a_{n}=(-1)^{n} \quad \{a_{n}\}=\{+1;-1;+1;-1+1-1;\dots\}$
1) $a_{n}$ è limitata $-1 \geq a_{n}\geq 1 \quad \forall n \in \mathbb{N}$
2) $a_{n}$ non è divergente  $\lim_{n \to \infty} a_{n} \neq \pm \infty$
3) $a_{n}$ non è convergente 
	Per assurdo $\lim_{n \to \infty}(-1)^{n}=1$
	$\forall \varepsilon > 0 \quad \exists n_{0}\in \mathbb{N} : \forall n \geq n_{0} \quad | (-1)^{n}-1| < \varepsilon$
	$n$ dispari: $|-1-1|<\varepsilon \rightarrow \varepsilon > 2$
	non vale $\forall \varepsilon > 0$ vale solo se $\varepsilon > 2$: assurdo

Esistono successioni  **Irregolari - indeterminate**

Che non sono divergenti nè convergenti