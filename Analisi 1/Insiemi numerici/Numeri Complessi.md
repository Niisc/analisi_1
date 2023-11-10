#### Definizione
I numeri complessi costituiscono un insieme che estende l'insieme dei [[Numeri reali]] ed in cui, a partire dalla definizione di unità immaginaria, è possibile estrarre le radici ad indice pari di numeri negativi e risolvere le equazioni di secondo grado con discriminante negativo.

Contengono i [[Numeri naturali]], [[Numeri interi]] e [[Numeri reali]].

## Campo Complesso
Estendendo in modo che ogni equazione polinomiale di grado $n$ abbia [[Teorema fondamentale dell'algebra|esattamente]] $n$ soluzioni (contate con la loro molteplicità):

Sia $\mathbb{R} \times \mathbb{R}$ l'insieme delle coppie ordinate di numeri reali $(a,b)\in \mathbb{R} \times \mathbb{R}$. Definisco le operazioni di **Somma** e **Prodotto** $\forall (a,b),(c,d)\in \mathbb{R} \times \mathbb{R}$ :
$$+:\quad(a,b)+(c,d)\ =\ (a+c,b+b)$$$$\cdot:\quad(a,b)\cdot(c,d)\ =\ (ac-bd,ad+bc)$$
>[!Example] Esempio
$\left(1;-5\right)+\left( \sqrt2;{\frac{1}{2}} \right)=\left( 1+\sqrt{2};-5+{\frac{1}{2}} \right)=\left( 1+\sqrt{ 2 };{-\frac{9}{2}} \right)$ $\left(1;-5\right)\cdot\left( \sqrt{2};{\frac{1}{2}} \right)=\left(\sqrt{2}+{\frac{5}{2}};{\frac{1}{2}}-5\sqrt{ 2 } \right)$ 

>[!info] Osservazione
>1) $\forall(a,b) \in \mathbb{R} \times \mathbb{R}\qquad (a,b)+(0,0)=(0,0)+(a,b)=(a,b)$ 
$$(0,0) \quad \text{Elemento Neutro per la somma}$$
>2) $\forall(a,b) \in \mathbb{R} \times \mathbb{R}\qquad (a,b)\cdot(1,0)=(1,0)\cdot(a,b)=(a,b)$ 
$$(1,0) \quad \text{Elemento Neutro per il prodotto}$$
>3) La somma e il prodotto godono della proprietà commutativa e associativa
>4) $\forall(a,b) \in \mathbb{R} \times \mathbb{R}$ esiste $(-a;-b)$ tale che:  
$$(a,b)+(-a,-b)=(-a,-b)+(a,b)=(0,0)\rightarrow (-a,-b)\ \text{elemento inverso della somma}$$
>5) $\forall(a,b) \in \mathbb{R} \times \mathbb{R}$ \ $\{(0,0)\}$:
$${\exists}!\normalsize\left( \frac{a}{a^2+b^2};\frac{-b}a^2+b^{2} \right)\quad\huge|\normalsize\quad(a,b)\cdot\left( \frac{a}{a^2+b^2};\frac{-b}{a^2+b^2} \right)=(1,0)$$ $\left( \frac{a}{a^2+b^2};\frac{-b}{a^2+b^2} \right)$ elemento inverso per il prodotto
$$\mathbb{R} \times \mathbb{R}\longrightarrow \mathbb{C}\quad \text{Campo Complesso}$$

>[!info] Osservazione
> $$\large \mathbb{C} \quad \text{estende} \quad \mathbb{R}$$
Tutti i numeri della forma $(a;0)$ sono numeri reali:
$$(a,0)+(c,0)=(a+c;0)\quad \forall a \in R$$
$$(a,0)\cdot(c;0)=(a \cdot c;0)$$
$$(a,0)\in \mathbb{R} \times \mathbb{R} \longleftrightarrow a\in R$$
[[Numerabilità#Corrispondenza Biunivoca|Corrispondenza biunivoca]] 

## Unità immaginaria
$$(0,1)+(0,1)=(0,2)$$
$$(0,1)\cdot(0,1)=(-1,0)=-1$$$(0,1)$ è il numero tale che il prodotto per se stesso è pari a -1.
#### Definizione
(0,1) si dice unità immaginaria $i$ tale che:
$$i^2=-1$$
## Scrittura
#### Forma algebrica
Ogni numero complesso $(a,b)$ si può scrivere come:
$$z=(a,b)=(a,0)+(0,b)=(a,0)+(0;1)(b,0)=\huge a+ib$$
Dove:
$a,b \in \mathbb{R}$
$a$ Parte Reale
$b$ Parte immaginaria
>[!example] Esempio
> $$z=1 + \sqrt{ 2 } i$$

#### Forma Trigonometrica
Considerando la rappresentazione di numeri complessi come punti del [[Piano di Gauss]] notiamo che possono essere individuati anche con le loro **Coordinate Polari**:

Da $z=a+ib$, si può ricavare:
$$a=\rho \cos \theta \qquad b=\rho \sin \theta$$
$$\large z=\rho(\cos \theta+i\sin \theta)$$
![[cd805084-fb73-44fd-909c-a2c1f2b2d18e.jpg|300]]

Dove:
$\large\rho$ Modulo
- Lunghezza del vettore $z$
- (Raggio polare= Distanza del punto dall'origine)

$\large\theta$ Argomento
- Angolo che il vettore $z$ forma con **l'asse reale positivo**
- (Angolo polare)

>[!example] Esempio
> $$z = \sqrt{ 2 } \left(  \cos \frac{\pi}{4} + i \sin \frac{\pi}{4} \right)$$

#### Forma Esponenziale
$$\large z=\rho e^{i\theta}$$
Identità di [[Numero di Nepero|Eulero]]
$$\large[e^{i\theta}=\cos \theta+i\sin \theta]$$
>[!example] Esempio
> $$z = \sqrt{ 2 } e^{i \pi/4}$$

#### Vantaggi e svantaggi:
- Somma e Differenza $\to$ Forma algebrica
- Prodotto e Quoziente $\to$ Forma Trigonometrica, Forma Esponenziale
- Potenza $\to$ [[Formula di De Moivre]]

>[!info] Osservazione
> $\theta,\rho, \text{con} \  \rho>0 \quad(\rho=0 \iff z=o)$ 
> Definiscono un determinato punto del piano, mentre un punto nel piano definisce univocamente la coordinata $\rho$, l'angolo $\theta$ non è unico: $\theta+2k\pi$ e $\theta$ definiscono lo stesso angolo
> $$\rho^{2}= a^{2}+b^{2}=|z|^{2}\longrightarrow|z|=\rho=\sqrt{ a^{2}+b^{2}}\geq 0$$

Per determinare $\theta$ :$$\begin{cases}
\rho \cos \theta=a \\
\rho \sin \theta=b \\
\end{cases}\quad\frac{b}{a}=\frac{\rho \sin \theta}{\rho \cos \theta}=\tan \theta,\quad \theta \not=\frac{\pi}{2}+k\pi $$
Tra $[0,2\pi]$ ho due angoli con la stessa tangente (data la periodicità della tangente)

## Coniugato
Dato $z \in \mathbb{C} \setminus \{0\} \quad z=a+ib$ definisco il Coniugato di z ovvero il numero complesso $$\overline{z}=a-ib$$
> [!info] Osservazione
> $$\large|z|=|\overline{z}|$$
$$Re(z)=Re(\overline{z})=a \qquad Im(z)=-Im(\overline{z})=b$$
$$|z|=|\overline{z}|=\rho$$
$$\overline{z}=\rho[\cos(-\theta)+i\sin(-\theta)]=\rho e^{-i\theta}$$
$$\arg(\overline z)=2\pi-\arg(z)$$
$$(2\pi-Arg(z)=-\ \theta)$$
![[07df121a-41cb-45ba-9dc5-66de0cfbaaa3.jpg|300]]

>[!info] Osservazione
>$\mathbb{C}$ Non è ordinato
#finire 
#### Proprietà
1) $z+\overline z=(a\cancel{ +ib })+(a\cancel{ -ib })=2a=2\mathrm{Re}(z)\in \mathbb{R}$
![[e8486692-819b-49eb-a8d6-687eb67fc34b.jpg|300]]
2) $z-\overline z=(\cancel{ a }+ib)-(\cancel{ a }-ib)=2ib=2i \cdot \mathrm{Im}(z) \rightarrow$ Numero immaginario puro
![[photo1696785653.jpeg|300]]
3) $z\cdot\overline z =(a+ib)\cdot(a-ib)=a^{2}-i^{2}b^{2}=a^{2}+b^{2}=|z|^{2}\in\mathbb{R},|z|^{2}\geq 0$
4) $\frac{z}{\overline z}=\frac{a+ib}{a-ib}\times\frac{a+ib}{a+ib}=\frac{a^{2}+2aib+i^{2}b^{2}}{a^{2}+b^{2}}=\mathrm{Re}\left(\frac{{a^{2}-b^{2}}}{{a^{2}+b^{2}}}\right)+ i\cdot \mathrm{Im}\left(\frac{2ab}{a^{2}+b^{2}}\right)$


> [!info] Osservazione
> $$\frac{\overline z}{z}$$
> $$\frac{\overline z}{z}=\mathrm{Re}\left(\frac{{a^{2}-b^{2}}}{{a^{2}+b^{2}}}\right)- i\cdot \mathrm{Im}\left(\frac{2ab}{a^{2}+b^{2}}\right)$$ 
> $$\frac{\overline z}{z}\times\frac{\overline z}{\overline z}=\frac{\overline z^{2}}{|z|^{2}}$$
> $$\frac{\overline z}{z}\times\frac{z}{z}=\frac{z^{2}}{|z|^{2}}$$
