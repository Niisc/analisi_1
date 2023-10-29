##### 1) Siano $a_n$ e $b_n$ due secessioni convergenti:
$$\lim_{n \to +\infty} a_{n} = l \quad \lim_{n \to +\infty} b_{n}= m$$
Allora:
1)
$$\lim_{n \to +\infty}(a_{n}\pm b_{n})= l \pm m$$
2)
$$\lim_{n \to +\infty} a_{n}\cdot b_{n}=l\cdot m$$
3)
$$\lim_{n \to +\infty}\frac{a_{n}}{b_{n}} = \frac{l}{m}\quad b_{n}\neq0 \quad m\neq 0$$
4)
$$\lim_{n \to +\infty}(a_{n})^{b_{n}} =l^{m} a_{n}\geq0 \quad l \geq0$$
##### Dimostrazione
$$\lim_{n \to +\infty}(a_{n}\pm b_{n})= l \pm m$$
$$\forall \varepsilon > 0 \quad \exists n_{0}\in \mathbb{N} : \forall n \geq n_{0} \quad |a_{n}-l| < \varepsilon$$
$$\forall \varepsilon > 0 \quad \exists n_{1}\in \mathbb{N} : \forall n \geq n_{1} \quad |a_{n}-m| < \varepsilon$$

Devo mostrare che $\forall \varepsilon > 0 \quad \exists \bar{n} \in \mathbb{N} : \quad \forall n \geq \bar{n}$:
$$|a_{n}+ b_{n}-(l+m)|< \varepsilon$$
Usando la [[Numeri reali#Valore assoluto. Disuguaglianza triangolare|disuguaglianza triangolare]]:

$$|a_{n}-b_{n}-l-m| = |(a_{n}- l)+(b_{n}-m)|\leq |{a_{n}-l| + |b_{n}-m| \leq 2 \varepsilon }$$
Vale per ogni $n \geq max\{n_{0},n_{1}\}$

scelgo $\bar{n} = max\{n_{0},n_{1}\}$ cosi che $\forall \varepsilon > 0 \ni \bar{n} : \forall n \geq \bar{n}$  

Poiché $\frac{1}{b_{n}} < \varepsilon$

Ovvero:

$$
\lim_{ n \to \infty } \left( \frac{a_{n}}{b_{n}} \right)=0
$$
##### 2) Sia $a_n$ una successione convergente e sia $b_n$ una successione divergente a $+ \infty$ 
$$\lim_{n \to +\infty} a_{n} = l \quad \lim_{n \to +\infty} = +\infty$$
Allora:
1)
$$\lim_{ n \to \infty } (a_{n}\pm b_{n}) = \pm \infty $$
2)
$$
\lim_{ n \to \infty } a_{n} \cdot b_{n} = \begin{cases}
+ \infty  & se  & l>0  & l\neq 0 \\
-\infty  &  se  & l < 0  & l\neq 0

\end{cases}
$$
3)
$$
\lim_{ n \to \infty } \frac{a_{n}}{b_{n}} = 0 \quad se \quad  a_{n} \neq 0 \quad l\neq 0
$$
4)
$$
\lim_{ n \to \infty } \frac{b_{n}}{a_{n}} = \begin{cases} +\infty & se  & l>0 & se & a_{n} \neq 0 \\
- \infty  & se  & l<0 & l\neq 0

\end{cases}
$$
5)
$$
\lim_{ n \to \infty } (a_{n})^{b_{n}} = \begin{cases}
+\infty  & se &  l>0  &  se & a_{n} \neq 0  & l \neq 0 \\
- \infty  & se  & l \neq 0
\end{cases}
$$
6)
$$
\lim_{ n \to \infty } (b_{n})^{a_{n}} = +\infty \quad se \quad a_{n} \quad l>0
$$
##### Dimostrazione
$$
\lim_{ n \to \infty } \frac{a_{n}}{b_{n}} = 0 \quad se \quad a_{n} \neq 0 \quad l\neq 0
$$
$$
\forall \varepsilon>0 \quad \exists n_{0} \in \mathbb{N} : \quad \forall n \geq n_{0} \quad |a_{n} -l | < \varepsilon
$$
$$
\forall\varepsilon>0 \quad \exists n_{1} \in \mathbb{N} : \quad \forall n \geq n_{1} \quad|b_{n}|>M
$$


Devo mostrare che $\forall \varepsilon > 0 \quad \exists \bar{n}\in \mathbb{N} : \forall n \geq \bar{n}$ si ha:

$$
\left|\frac{a_{n}}{b_{n}}-0\right|<\varepsilon
$$

$a_{n}$ è convergente $\rightarrow$ $a_{n}$ è limitata definitivamente
$$
a_{n}<l+\varepsilon < |l| + \varepsilon \quad \forall n \geq n_{2}
$$

Posso supporre  che $b_{n}>\frac{1}{\varepsilon}$ perché $b_{n}>M \quad \forall M >0$

Allora $\forall \varepsilon >0 \quad \exists \bar{n}=\max\{n_{0},n_{1},n_{2}\}$ tale che $\forall n>\bar{n}$
$$
\left|\frac{a_{n}}{b_{n}} \right|-0 < (|l|+\varepsilon) = k\varepsilon
$$Poiché $\frac{1}{b_{n}}<\varepsilon$ 
$$
\lim_{ n \to \infty } \left( \frac{a_{n}}{b_{n}} \right)=0
$$

##### 3) Siano $a_{n}$ e $b_{n}$ due successioni divergenti a $+ \infty$ 
$$
\lim_{ n \to \infty } a_{n}=+ \infty \quad \lim_{ n \to \infty } b_{n}=+\infty
$$
allora:
1)
$$
\lim_{ n \to \infty } (a_{n}+b_{n})=+\infty
$$
2)
$$
\lim_{ n \to \infty } a_{n} \cdot b_{n}=+\infty
$$
##### Dimostrazione
$$
\lim_{ n \to \infty } (a_{n}+b_{n})=+\infty
$$
$$
\forall M>0 \quad \exists n_{0} \in \mathbb{N}:\quad \forall n> n_{0} \quad a_{n}>M
$$
$$
\forall M>0 \exists n_{1} \in \mathbb{N}: \quad \forall n > n_{1} \quad b_{n}>M
$$
Devo mostrare che $\forall M>0 \quad \exists \bar{n} \in \mathbb{N}:\quad \forall n \geq \bar{n} \quad a_{n}+b_{n}>M$
Scelgo come $\bar{n} = max\{n_{0},n_{1}\}$ cosi che $\forall M\gg 0 \quad \exists \bar{n}:\quad \forall n \geq \bar{n}$

$$
a_{n}+b_{n} > M+M=2M>M
$$

>[!info] Osservazione
>$$\lim_{ n \to \infty } (a_{n}-b_{n})=?$$
> Forma di indeterminazione $[\infty - \infty]$

>[!example] Esempio
> $$\lim_{ n \to \infty } (5n^7-n^9)$$
> $$a_{n}=5n^{7} \quad \lim_{ n \to \infty } 5n^{7}=+\infty$$
> $$b_{n}=n^{9} \quad \lim_{ n \to \infty } n^{9}=+\infty$$
> $$\lim_{ n \to \infty } 5n^{7}-n^{9}=\lim_{ n \to \infty } n^{7} \cdot (5-n^{2}) = -\infty$$
> $$=\lim_{ n \to \infty } n^{9} \left(  \frac{5}{n^{2}} -1 \right)$$
> $$\lim_{ n \to \infty } n^{9} \left( \frac{5}{n^{2}} -1 \right) = -\infty$$
> Dove $n^{9}$ è una successione divergente e $\left( \frac{5}{n^{2}}-1 \right)$ è una successione convergente a -1 $\rightarrow \infty \cdot -1 = - \infty$

>[!info] Osservazione
> $$\lim_{ n \to \infty } \frac{a_{n}}{b_{n}}=?$$
> Forma di indeterminazione $\left[ \frac{\infty}{\infty} \right]$
>

>[!example] Esempio
> $$\lim_{ n \to \infty } \frac{\sqrt{ n }+n^{8}-n^{2}}{7n^{3}-3n^{7}+n^{10}}$$
> $$a_{n} = \sqrt{ n } + n^{8} -n^{2}$$
> $$b_{n}=7n^{3}-3n^{7}+n^{10}$$
> $$\lim_{ n \to \infty } \frac{{n^{7}\left( 1+\frac{8}{n^{4}}-\frac{1}{n^{6}\sqrt{ n }} \right)}}{n^{5}\left( -1+\frac{1}{n^{3}}+\frac{1}{n^{5}} \right)}$$
> Dove:
> $$\lim_{ n \to \infty } \frac{8}{n^{4}}=\lim_{ n \to \infty } \frac{1}{n^{6} \sqrt{ n }}=\lim_{ n \to \infty } \frac{1}{n^{3}}=\lim_{ n \to \infty } \frac{1}{n^{5}}=0$$
> $$\lim_{ n \to \infty } \left( 1+\frac{8}{n^{4}}-\frac{1}{n^{6}\sqrt{ n }} \right)=1$$
$$\lim_{ n \to \infty } \left( -1+\frac{1}{n^{2}}+\frac{1}{n^{5}} \right)=-1$$
$$=\lim_{ n \to \infty } n^{2} \cdot \frac{1}{-1}=- \infty$$

>[!example] Esempio
> $$\lim_{ n \to \infty } \ln\left( \frac{{n^{3}+2n^{2}}}{n 2^{n}} \right)$$
> $$\lim_{ n \to \infty } \frac{{n^{3}+2n^{2}}}{2^{n}n}=\lim_{ n \to \infty } \frac{{n^{\overbrace{ \cancel{ 3 } }^{ 2 }}\left( 1+\frac{2}{n} \right)}}{2^{n}\cancel{ n }}$$
> Dove: $\lim_{ n \to \infty } \frac{2}{n}=0$
> $$=\lim_{ n \to \infty } \frac{{n^{2}\cdot 1}}{2^{n}}=0$$
> $$=\lim_{ n \to \infty } \ln\underbrace{ \left( \frac{{n^{3}+2n}}{n 2^{n}} \right) }_{ =0 }=- \infty$$

>[!info] Osservazione
>Data $a_{n}$ successione convergente a $0$ e data $b_{n}$ successione divergente a $+ \infty$
> $$\lim_{ n \to \infty } a_{n}\cdot b_{n} = ?$$
> Forma di indeterminazione $[0 \cdot \infty]$


