### Definizione
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

- **Converge** se esiste finito $\lim_{ k \to \infty } s_{k} = s$
(la successione $s_{k}$ converge)
$s$ è detta somma della serie
- **Diverge** a $+ \infty$ (o $- \infty$) se la successione $s_{k}$ diverge a $+ \infty$ ($- \infty$) $\lim_{ k \to \infty } s_{k} = + \infty$ o ($-\infty$)
- **Irregolare** se la successione $s_{k}$ è irregolare ovvero non esiste limite di $s_{k}$
### Serie note
##### 1) Serie armonica
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

#### 3) Serie geometrica
$$\sum^{\infty}_{{n=0}}q^{n} = \lim_{ n \to \infty } s_{n}=\lim_{ n \to \infty } \sum^{n}_{k=0}a_{k} = \lim_{ n \to \infty } \frac{{1-q^{n+1}}}{1-q}$$

Dove $q$ è la ragione.

Analizzando $q$ si può dire: 
$$\frac{{1-q^{n+1}}}{1-q}=\begin{cases}
+ \infty & q \geq 1 \\
\frac{1}{1-q} & -1<q<1 \\
\text{Irregolare}  & q \leq -1
\end{cases}$$

### Condizioni per la convergenza

##### 1) Condizione necessaria alla convergenza

Se $\sum^{\infty}_{{n=0}} a_{n}$ converge allora $\lim_{ n \to \infty } a_{n} = 0$

>[!example] Esempio
>$\sum^{\infty}_{n=1}{\frac{1}{n^{2}}}$ converge $\Rightarrow \lim_{ n \to \infty } a_{n} = 0$
>$\sum^{\infty}_{n=1}{\frac{1}{n^{2}}}$ converge $\cancel{ \Leftarrow } \lim_{ n \to \infty } a_{n} = 0$

##### 2) Condizione sufficiente alla convergenza

Se $\sum^{\infty}_{n=0} |a_{n}|$ converge allora $\sum^{\infty}_{n=0} a_{n}$ converge

$$\underbrace{ \sum^{\infty}_{n=0} |a_{n}| }_{ \text{Convergenza assoluta} } \Longrightarrow \underbrace{ \sum^{\infty}_{n=0} a_{n} }_{ \text{Convergenza semplice}}$$
