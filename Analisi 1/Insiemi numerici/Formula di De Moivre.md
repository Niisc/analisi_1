#lezione5
#### Formula Generalizzata:
$$z^n=\rho^n[\cos n\theta+i\sin n\theta]$$
Significato geometrico
$\rho^{n}$ : contrazione o dilatazione di $\rho$ 
$n\theta$ : rotazione di un angolo per ogni n
#### Dimostrazione
>[!tip] Suggerimento
> La formula di De Moivre utilizza la moltiplicazione tra numeri complessi

Dati:
$$z=a+ib=\rho\big[\cos \theta+i\sin\theta\big] \quad w=c+id=\micro\big[\cos \phi+i\sin\phi\big]$$
Calcoliamo $z \cdot w$:
$$z \cdot w=\rho\big[\cos \theta+i\sin\theta\big] \cdot \micro\big[\cos \phi+i\sin\phi\big]=$$
$$=\rho \cdot \micro\big[\cos \theta\cos \phi+i^{2}\sin\theta\sin\phi+i\cos \theta\sin \phi+i\sin\theta\cos\phi\big]=$$
$$=\underbrace{\rho\micro}_{ \text{prodotto moduli}}\big[(\cos\underbrace{(\theta+\phi)}_{\text{somma degli argomenti}}+i\sin\underbrace{(\theta+\phi)}]=$$
Se $z=w$
$$\begin{cases}
\rho= \micro \\
\theta=\phi \\ 
\end{cases}$$
$$z^{2}=\rho^{2}[\cos 2\theta+i\sin 2\theta]$$
Questo procedimento può essere fatto $n$ volte anziché 2 (come fatto sopra), così ricavando la formula generale.

> [!info] Osservazione
Ciclicità di $\mathbb{C}$:
>$$z=i=1 \cdot \left[ \cos\left( \frac{\pi}{2} \right)+i\sin\left( \frac{\pi}{2} \right) \right]=\large i$$
> $$z^{2}=i^{2}=1 \cdot \left[ \cos\left( \pi \right)+i\sin\left(\pi\right) \right]=\large-1$$ 
>$$z^{3}=i^{3}=1 \cdot \left[ \cos\left( \frac{3\pi}{2} \right)+i\sin\left( \frac{3\pi}{2} \right) \right]=\large -i$$ 
>$$z^{4}=i^{4}=1 \cdot \left[ \cos\left(2 \pi \right)+i\sin\left(2\pi\right) \right]=\large1$$ 
>$$z^{5}=i^{5}=1 \cdot \left[ \cos\left( \frac{\pi}{2} \right)+i\sin\left(\frac{\pi}{2}\right) \right]=\large i$$ 
> $$\dots$$
> ![[msg1048603746-11738.jpg|200]]

#finire
