![[Serie#3) Serie Geometrica]]

Considero la successione: $$\{S_{k}\}=\bigg\{\frac{1-q^{k+1}}{1-q}\bigg\}$$
Ne calcolo il limite $$\lim_{ n \to \infty }\frac{1-\color{orange}q^{k+1}}{1-q}$$
>[!info]
>L'andamento del limite dipende solo da $q^{k+1}$: 
 $\lim_{  n \to \infty }q^{k+1}=\begin{cases} 0, &se\  |q|<1\\ +\infty, & \mbox{se } q\geq 1 \\ non\ esiste, & \mbox{se } q\leq -1\end{cases}$ Quindi $\lim_{  n \to \infty }S_{k}=\begin{cases} \frac{1}{1-q}, &se\  |q|<1\\ +\infty, & \mbox{se } q\geq 1 \\ non\ esiste, & \mbox{se } q\leq -1\end{cases}$ 

La serie: $$\sum ^{\infty}_{n=0}q^{n}=\begin{cases}
+ \infty & q \geq 1 \\
\frac{1}{1-q} & -1<q<1 \quad (|q|<1) \\
\text{Irregolare}  & q \leq -1
\end{cases}$$