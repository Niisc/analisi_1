#### Definizione
Data una [[Successioni|successione]] numerica $\large \{a_n\}_{n\in \mathbb{N}}$ diciamo serie numerica la scrittura: $$\sum^{+\infty}_{n=0}a_n$$
La [[Sommatoria]] infinita della successione $a_{n}$.

Si può anche definire le somme parziali $s_{k}$:
$$s_{0} = a_{0}$$
$$s_{1}=a_{0}+a_{1}$$
$$s_{2}=a_{0}+a_{1}+a_{2}$$
$$s_{n} = a_{0}+a_{1}+a_{2}+\dots+a_{n}$$
Che si può definire usando una [[Sommatoria]]:
$$s_{k}=\sum^{k}_{n=0}a_{n}$$
>[!warning] Attenzione
> Non bisogna confondere $a_{n}$ con $s_{k}$.

Si dice che la serie $\sum^{\infty}_{n=0} a_{n}$ :

#### Convergente
Esiste finito: $$\lim_{  k \to +\infty }S_{k}=S$$
(La successione $S_{k}$ converge)
Dove $S$ è detto somma della serie.
#### Divergente
A $+\infty$ (o $-\infty$) se la successione $S_k$ diverge a $+\infty$ (o $-\infty$)
$$\lim_{  k \to +\infty }S_{k}=+\infty (-\infty) $$
#### Irregolare
La successione $S_{k}$ è irregolare, ovvero non esiste limite di $S_{k}$

## Serie note
#### 1) [[Serie Armonica]]
$$1 + \frac{1}{2} + \frac{1}{3} + \frac{1}{4} + \dots + \frac{1}{n}=\sum^{+ \infty}_{n=1}\frac{1}{n}$$
![[Serie 2023-10-25 22.47.51.excalidraw]]

>[!attention] Attenzione
> Anche se $$\lim_{ n \to \infty } \frac{1}{n} = 0$$ 
> La serie diverge a $+ \infty$ $$\sum^{\infty}_{n=1}\frac{1}{n}=+ \infty$$

#### 2) Serie armonica generalizzata

Definita come
$$\sum^{\infty}_{n=1}\frac{1}{n^{\alpha}} \quad \alpha \in \mathbb{R}$$
Se $\alpha > 1$ allora la serie converge
Se $\alpha \leq 1$ allora la serie diverge

>[!example] Esempio
> $$\alpha = 2 \quad \sum^{\infty}_{n=1} \frac{1}{n^{2}} = 1 + \frac{1}{4}+\frac{1}{9}+ \dots + \frac{1}{n^{2}}$$
> $$\alpha = \frac{1}{2} \quad \sum^{\infty}_{n=1} \frac{1}{n^{\frac{1}{2}}} = 1 + \frac{1}{\sqrt{ 2 }} + \frac{1}{\sqrt{ 3 }} + \dots+ \frac{1}{\sqrt{ n }}$$

#### 3) [[Serie Geometrica]]
Sia $a_{n}=q^{n}, q \in \mathbb{R}$ ([[Progressione Geometrica]]).
$S_{0}=q^{0=1\quad}S_{1}=q^{0}+q^{1}=1+q \quad S_{2}=q^{0}+q^{1}+q^{2}=1+q+q^{2}\dots$
Se $q \not= 1$ abbiamo (per [[Principio di induzione]]): 
$$S_{k}=\sum^{k}_{n=0}q^{k}= \frac{1-q^{k+1}}{1-q}$$
Se invece q=1 abbiamo $S_{n}=n+1$.
>[!warning]
>La serie:
>$$\sum ^{\infty}_{n=0}q^{n}=\begin{cases} + \infty & q \geq 1 \\\frac{1}{1-q} & -1<q<1 \quad (|q|<1) \\\text{Irregolare}  & q \leq -1\end{cases}$$
#### 4) Serie di Mengoli
$$\sum ^{\infty}_{n=1}\frac{{1}}{n(n+1)}$$ Osservando che $\frac{{1}}{n(n+1)}=\frac{1}{n}-\frac{1}{n+1}$ allora notiamo che:
$$S_{n}=\sum ^{n}_{k=1} \left[\frac{1}{k}- \frac{{1}}{k+1}\right]=\left[ 1-\frac{1}{2} \right]+\left[ \frac{1}{2}-\frac{1}{3} \right]+\dots+\left[ \frac{1}{n
}-\frac{1}{n+1} \right]$$
Semplificando a 2 a 2:
$$=1-\frac{1}{n+1}$$
$S_{k}=\lim_{  k \to +\infty }\left( 1-\frac{1}{k+1} \right)=1$
La serie converge a 1
La serie di Mengoli è il più semplice esempio di [[Serie Telescopiche]]

## Condizioni per la convergenza

#### 1) [[Condizione necessaria per la convergenza]]

Data una successione $a_{n}$ , affinché la serie $\sum^{\infty}_{{n=0}} a_{n}$ converga è necessario che
$$\lim_{ n \to \infty } a_{n} = 0$$
Quindi: Se $\sum^{+\infty}_{n=0}a_{n}$ converge, allora $\lim_{ n \to +\infty }a_{n}=0$

>[!example] Esempio
>$\sum^{\infty}_{n=1}{\frac{1}{n^{2}}}$ converge $\Rightarrow \lim_{ n \to \infty } a_{n} = 0$

>[!warning] Attenzione
>Non vale il contrario:
$\lim_{ n \to \infty } a_{n} = 0 \cancel{ \Rightarrow } \sum^{\infty}_{n=1}{\frac{1}{n^{2}}}$ converge
>Esempio:
>$\lim_{ n \to \infty } a_{n} = 0$ ma $\sum^{\infty}_{n=1}{\frac{1}{n}}$ diverge ([[Serie Armonica]])
#### 2) Condizione sufficiente alla convergenza ([[Criterio di convergenza assoluta]])

Se $\sum^{\infty}_{n=0} |a_{n}|$ converge allora $\sum^{\infty}_{n=0} a_{n}$ converge semplicemente

$$\underbrace{ \sum^{\infty}_{n=0} |a_{n}| }_{ \text{Convergenza assoluta} } \Longrightarrow \underbrace{ \sum^{\infty}_{n=0} a_{n} }_{ \text{Convergenza semplice}}$$

>[!info]
>Vale la seguente disuguaglianza:
>$$\left| \sum^{+\infty}_{n=0}a_{n} \right| \leq \sum^{+\infty}_{n=0} |a_{n}|$$

>[!warning] Attenzione
>$$\underbrace{ \sum^{\infty}_{n=0} |a_{n}| }_{ \text{Convergenza assoluta} } \cancel{ \Longleftarrow } \underbrace{ \sum^{\infty}_{n=0} a_{n} }_{ \text{Convergenza semplice}}$$

## Criteri di convergenza
Si applicano **solo** se la serie è a [[Serie a termini positivi|termini positivi]] $\sum^{\infty}_{n=0} a_{n}\quad a_{n}>0 \quad \forall n \in \mathbb{N}$ (o per $n>{n_{0}}$)

#### [[Criterio del confronto di serie|Criterio del confronto di serie]]
Siano:
$$\sum^{\infty}_{n=0} a_{n} \quad \sum^{\infty}_{n=0} b_{n}$$
Serie numeriche a [[Serie a termini positivi|termini positivi]] tali che:
$$a_{n} \leq b_{n} \quad \forall n \geq n_{0}$$
Allora:

1) se la serie $\sum^{\infty}_{n=0} b_{n}$ converge, allora converge anche $\sum^{\infty}_{n=0} a_{n}$
2)  Se la serie $\sum^{\infty}_{n=0} a_{n}$ diverge, allora diverge anche $\sum^{\infty}_{n=0} b_{n}$


> [!example] Esempio
> $$\sum^{\infty}_{n=1} \frac{n^{3}}{e^{n}} \quad e^{n}>n^{\alpha} \quad \forall \alpha$$
> $$\alpha = 5 \rightarrow \frac{1}{e^{n}} < \frac{1}{n^{\alpha}}$$
$$a_{n}=\frac{n^{3}}{e^{n}}<\frac{n^{3}}{n^{5}}=\frac{1}{n^{2}}$$

#### [[Criterio del rapporto di Serie| Criterio del rapporto]]

$$\sum^{\infty}_{n=0} a_{n} \quad a_{n}>0 \quad \forall n$$
$$\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}}=\beta \quad \begin{cases}
\beta < 1 & \sum a_{n} & \text{converge}  \\
\beta = 1 & &  \text{non si può dire}  \\
	\beta > 1 & \sum a_{n} & \text{ diverge}
\end{cases}$$
> [!example] Esempio
> $$\sum^{\infty}_{n=0} \frac{n^{3}}{e^{n}} \quad a_{n}=\frac{n^{3}}{e^{n}}\geq 0 \quad \forall n$$
$$\lim_{ n \to \infty } \frac{a_{n+1}}{a_{n}} = \lim_{ n \to \infty } \frac{(n+1)^{3}}{e^{n}e} \cdot \frac{e^{n}}{n^{3}}= \lim_{ n \to \infty } \frac{n^{3}}{n^{3}e} = \frac{1}{e} < 1$$
Quindi: $a_{n}$ converge

#### [[Criterio della radice di Serie]]
$$\sum a_n \quad a_n \geq 0 \quad \forall n$$
$$\lim_{ n \to \infty } (a_{n})^{1/n} = \alpha \quad \begin{cases}
\alpha > 1 & \text{diverge} \\
\alpha = 1  & \text{non si può dire}  \\
\alpha <1  & \text{converge} 
\end{cases}$$

#### [[Criterio del confronto asintotico di serie]]
Siano $\sum^{\infty}_{n=0} a_{n}$ e $\sum^{\infty}_{n=0} b_{n}$ due serie a [[Serie a termini positivi|termini positivi]] tali che
$$a_{n} \sim b_{n} \quad \text{per} \quad n \to + \infty$$
$$\lim_{ n \to \infty } \frac{a_{n}}{b_{n}} =1$$
Allora le due serie hanno lo stesso carattere.
