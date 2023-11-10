#lezione11
![[Serie#1) Condizione necessaria per la convergenza]]
#### Dimostrazione
Per ipotesi: $\sum a_{n}$ converge
Tesi: $\lim_{ n \to +\infty }a_{n}=0$

Costruisco $S_{k}= \sum^{k}_{n=0}a_{n}$
Osservo:
$$S_{k+1}=\sum^{k+1}_{n=0}a_{n}=\underbrace{\sum^{k}_{n=0}a_{n}}_{S_{k}}+a_{k+1}$$
$S_{k}+1=S_{k}+a_{k+1}$ quindi $\rightarrow a_{k+1} =S_{k+1}-S_{k}$
Sappiamo che il $\lim_{ n \to +\infty }S_{k}=S$
Allora $$\lim_{ k \to +\infty } a_{k+1}=\lim_{ k \to +\infty }S_{k+1}-S_{k}=\underbrace{\lim_{  k \to +\infty } S_{k+1}}_{S}-\underbrace{\lim_{  k \to +\infty } S_{k}}_{S}=\cancel S- \cancel S=0$$
$$\lim_{  k \to +\infty } a_{k+1}=0 \text{ ovvero:} \huge\lim_{ n \to +\infty } a_{n}=0$$
