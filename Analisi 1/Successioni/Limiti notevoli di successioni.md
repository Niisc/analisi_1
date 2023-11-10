>[!info] Osservazione
>Dal [[Numero di Nepero|limite di Nepero]] 
>$$\lim_{ n \to \infty }\left( 1+\frac{1}{b_{n}} \right)^{b_{n}}=e$$
>Si possono ricavare altri limiti

1) Se $b_{n} \to + \infty$ allora $\varepsilon_{n} = \frac{1}{b_{n}} \to 0$

$\varepsilon_{n}$ è infinitesimo $\lim_{ n \to \infty } \varepsilon_{n} =0$
$$\large \color{orange}\lim_{ n \to \infty } (1+\varepsilon_{n})^{1/\varepsilon_{n}}=e$$
2) Calcolo il logaritmo naturale di entrambi i membri

$$\lim_{ n \to \infty } \ln(1+\varepsilon_{n})^{1/\varepsilon_{n}}=\ln e=1$$

$$\large \color{orange} \lim_{ n \to \infty } \frac{\ln(1+\varepsilon_{n})}{\varepsilon_{n}}=1 \quad \varepsilon_{n \to_{0}}$$
3) Poniamo $\varepsilon_{n} =e^{\delta_{n}}-1 \rightarrow e^{\delta_{n}} = \varepsilon_{n} +1$
se $\varepsilon_{n} \to 0$ allora $\delta_{n} \to 0$
$$\lim_{ n \to \infty } \frac{\ln(1+\varepsilon_{n})}{\varepsilon_{n}} = \lim_{ n \to \infty } \frac{\delta_{n}}{e^{\delta_{n}}-1}=1$$
$$\color{orange} \large \lim_{ n \to \infty } \frac{{e^{\delta_{n}}-1}}{\delta_{n}}=1 \quad \delta_{n} \to 0$$

4) Poniamo $\varepsilon_{n} =(1+ \phi_{n})^{\alpha}-1 \to (1+\phi_{n})^{\alpha}= \varepsilon_{n}+1 \to 1+ \phi_{n}=(\varepsilon_{n}+1)^{1/\alpha}$
$$\phi_{n}=(\varepsilon_{n}+1)^{1/\alpha}-1$$
Se $\varepsilon_{n} \to 0$ allora $\phi_{n} \to 0$
$$\lim_{ n \to \infty } \frac{\ln(1+\varepsilon_{n})}{\varepsilon_{n}}=\lim_{ n \to \infty } \frac{\ln(\cancel{ 1+ }(1+C\phi_{n})^{\alpha}\cancel{ -1 })}{(a+\phi_{n})^{\alpha}-1}$$
$$=\lim_{ n \to \infty } \frac{\alpha \ln(1+\phi_{n})}{(1+\phi_{n})^{\alpha}-1}=\lim_{ n \to \infty } \frac{\alpha \phi_{n}}{(1+\phi_{n})^{\alpha}-1} \cdot \underbrace{ \frac{\ln(1+\phi_{n})}{\phi_{n}} }_{ =1 } =1$$

	$$\large \color{orange} \lim_{ n \to \infty } \frac{{(a+\phi_{n})^{\alpha}-1}}{\phi_{n}}=\alpha \quad \phi_{n \to 0}$$

>[!info] Osservazione
>I limiti 2) 3) 4) sono forme di indeterminazione $\left[ \frac{0}{0} \right]$

5) Sia $\varepsilon_{n}$ una [[Successioni|successione]] infinitesima $\lim_{ n \to \infty }\varepsilon_{n}=0$

$$\color{orange} \large \lim_{ n \to \infty } \frac{\sin(\varepsilon_{n})}{\varepsilon_{n}}=1$$
##### Dimostrazione
Per $x \in (0; \frac{\pi}{2}) \quad \sin(x)\leq x\leq \tan(x)$
$A = (1,0) \quad P = (\cos(x),\sin(x)) \quad T=(1,\tan(x))$
![[Pasted image 20231027174608.png|300]]
$$\underbrace{ \mathrm{Area}(AOP) }_{ \large \frac{1}{2}\sin(x) } \leq \underbrace{ \mathrm{Area}(\mathrm{Settore (AOP)}) }_{\large \frac{x}{2} } \leq \underbrace{ \mathrm{Area}(AOT) }_{\large \frac{1}{2}\tan(x) }$$

Da finire

6) Per $\varepsilon_{n} \to 0$
$$\color{orange} \large \lim_{ n \to \infty } \frac{{1-\cos(\varepsilon_{n})}}{(e_{n})^{2}}=\frac{1}{2}$$

>[!attention] Attenzione
> $a_{n}$ è **infinitesima** se $\lim_{ n \to \infty }a_{n}=0$
> $a_{n}$ è **infinita** se $\lim_{ n \to \infty } a_{n} = \infty$

Siano $a_{n}$ e $b_{n}$ [[Successioni]] infinite. Allora: 
Caso $\left[ \frac{\infty}{\infty} \right]$
$$\lim_{ n \to \infty } \frac{a_{n}}{b_{n}}= \begin{cases}
0 & \text{ $a_{n}$ è di ordine inferiore rispetto a $b_{n}$} \\
l \neq 0 & \text{$a_{n}$ e $b_{n}$ hanno lo stesso ordine di infinito} \\
\infty & \text{$a_{n}$ è di ordine superiore rispetto a $b_{n}$} \\
\text{non esiste} & \text{$a_{n}$ e $b_{n}$ non sono confrontabili}

\end{cases}$$

Siano $a_{n}$ e $b_{n}$ [[Successioni]] infinitesime. Allora: 
Caso $\left[ \frac{0}{0} \right]$
$$\lim_{ n \to \infty } \frac{a_{n}}{b_{n}}= \begin{cases}
0 & \text{ $a_{n}$ è di ordine superiore rispetto a $b_{n}$} \\
l \neq 0 & \text{$a_{n}$ e $b_{n}$ hanno lo stesso ordine di infinitesimo} \\
\infty & \text{$a_{n}$ è di ordine inferiore rispetto a $b_{n}$} \\
\text{non esiste} & \text{$a_{n}$ e $b_{n}$ non sono confrontabili}

\end{cases}$$

>[!Attention] Caso particolare
> se $l=1$
>  se $\lim_{ n \to \infty }\frac{a_{n}}{b_{n}}=1$ si dice che $a_{n}$ e $b_{n}$ sono **Asintotiche**
>  $a_{n} \sim b_{n}$ per $n \to \infty$

>[!info] Osservazione
>Se $a_{n} \sim b_{n}$, allora le due successioni hanno lo stesso carattere (convergono o divergono o sono irregolari)

>[!info] Osservazione
>La relazione $\sim$ è una [[Relazioni#Relazione d'equivalenza|relazione d'equivalenza]]
> - riflessiva $a_{n} \sim a_{n} \quad \lim_{ n \to \infty } \frac{a_{n}}{a_{n}}=1$
> - simmetrica $a_{n}\sim b_{n} \rightarrow b_{n} \sim a_{n} \quad \lim_{ n \to \infty } \frac{a_{n}}{b_{n}} =1 \rightarrow \lim_{ n \to \infty } \frac{b_{n}}{a_{n}} = \lim_{ n \to \infty } \frac{1}{\frac{a_{n}}{b_{n}}}=1$
> - transitiva $a_{n} \sim b_{n}$ e $b_{n} \sim c_{n} \rightarrow a_{n}\sim c_{n}$ (da dim)

>[!example] Esempio
> $$\lim_{ n \to \infty } \frac{{n^{3}+n^{7}}}{n^{4}-n^{8}} = \lim_{ n \to \infty } \frac{\cancel{ n^{7} }\left( 1+\frac{1}{n^{4}} \right)}{n^{\cancel{ 8 }}\left( -1+\frac{1}{n^{4}} \right)} = \lim_{ n \to \infty } \frac{1}{n} = 0$$
> $b_{n}$ è un infinito di ordine superiore rispetto ad $a_{n}$

## Gerarchia degli infiniti
1) Sia $a_{n} = \log_{b}(n)$ con $n \geq 1 \quad b>1$
$$\lim_{ n \to \infty } \log_{b}(n)= + \infty$$
2) sia $b_{n} = n^{\alpha}$ con $\alpha>0$
$$\lim_{ n \to \infty } n^{\alpha}= + \infty$$
3) sia $c_{n} = q^{n}$ con $n \geq 0 \quad q>1$
$$\lim_{ n \to \infty } q^{n}= + \infty$$

#### Teorema
Valgono i seguenti limiti
1) $$\lim_{ n \to \infty } \frac{\log_{b}(n)}{n^{\alpha}}=0 \quad \forall b>1 \quad \forall \alpha>0$$
2)  $$\lim_{ n \to \infty } \frac{n^{\alpha}}{q^{n}}=0 \quad \forall q>1 \quad \forall \alpha > 0$$
3) $$\lim_{ n \to \infty } \frac{q^{n}}{n!}=0 \quad \forall q>1$$
4) $$\lim_{ n \to \infty } \frac{n!}{n^{n}}=0 $$
