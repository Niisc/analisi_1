![[! Numeri Reali#Campo Complesso]]
## Osservazione: $\mathbb{C}$ estende $R$:
##### Tutti i numeri della forma $(a;0)$ sono numeri reali:
$$(a,0)+(c,0)=(a+c;0)\quad \forall a \in R$$
$$(a,0)*(c;0)=(ac;0)\qquad \qquad$$
$\LARGE(a,0)\in RxR \longleftrightarrow a\in R$ **Corrispondenza Biunivoca**
[[Numerabilità#Corrispondenza Biunivoca]] 
#lezione4
# Unità immaginaria
$$(0,1)+(0,1)=(0,2)$$
$$\huge(0,1)*(0,1)=(-1,0)=-1$$$(0,1)$ è il numero tale che il prodotto per se stesso è pari a -1.
### Definizione
(0,1) si dice unità immaginaria $i$ tale che:
$$i^2=-1$$
## Scrittura
#### Forma algebrica
Ogni numero complesso $(a,b)$ si può scrivere come:
$$z=(a,b)=(a,0)+(0,b)=(a,0)+(0;1)(b,0)=\huge a+ib$$
Dove:
$a$ **Parte Reale** $\qquad a,b \in \mathbb{R}$
$b$ **Parte immaginaria**
#### Piano complesso (Piano di Gauss)
Si può rappresentare il Campo complesso in un piano cartesiano con i numeri complessi $a+ib$ come punti di coordinate $(a,b)$ . Il piano prende il nome di **Piano di Gauss**, i cui assi sono rispettivamente l'asse reale (ascisse) e l'asse immaginario (ordinate), i punti sull'asse reale sono numeri reali, i numeri sull'asse immaginario sono numeri *immaginari puri* ($ib$).

#### Forma Trigonometrica
Considerando la rappresentazione di numeri complessi come punti del piano di Gauss notiamo che possono essere individuati anche con le loro **Coordinate Polari**: 
![[cd805084-fb73-44fd-909c-a2c1f2b2d18e.jpg|300]]
##### $\large\rho$ Modulo
Lunghezza del vettore $z$
(Raggio polare= Distanza del punto dall'origine)
##### $\large\theta$ Argomento
Angolo che il vettore $z$ forma con **l'asse reale positivo**
(Angolo polare)

###### Dato il numero $z=a+ib$, dalla trigonometria ricaviamo le relazioni tra le coordinate cartesiane e quelle polari: $$a=\rho \cos \theta \qquad b=\rho \sin \theta$$
E da qui la **Forma Trigonometrica:
$$\huge z=\rho(\cos \theta+i\sin \theta)$$
#### Forma Esponenziale
$$\huge z=\rho e^{i\theta}$$
$$\large[e^{i\theta}=\cos \theta+i\sin \theta]\qquad Identità\ di\ Eulero$$
### Vantaggi e svantaggi:
- Somma e Differenza $\longleftrightarrow$ Forma algebrica
- Prodotto e Quoziente $\longleftrightarrow$ Forma Trigonometrica, Forma Esponenziale
- Potenza $\longleftrightarrow$ [[!Formula di De Moivre]]
#domanda

#### Osservazione: $\theta,\rho, con\  \rho>0 \quad(\rho=0 \iff z=o)$ 
Definiscono un determinato punto del piano, mentre un punto nel piano definisce univocamente la coordinata $\rho$, l'angolo $\theta$ non è unico: $\theta+2k\pi$ e $\theta$ definiscono lo stesso angolo
#### Osservazione: $\rho^{2}= a^{2}+b^{2}=|z|^{2}\longrightarrow|z|=\rho=\sqrt{ a^{2}+b^{2}}\geq 0$

Per determinare $\theta$ :$$\begin{cases}
\rho \cos \theta=a \\
\rho \sin \theta=b \\
\end{cases}\quad\frac{b}{a}=\frac{\rho sen \theta}{\rho \cos \theta}=\tan \theta,\quad \theta \not=\frac{\pi}{2}+k\pi $$
Tra $[0,2\pi]$ ho due angoli con la stessa tangente (data la periodicità della tangente)
### Coniugato
Dato $z \in \mathbb{C}-\{0\} z=a+ib$ definisco il **Coniugato** di z ovvero il numero complesso $$\overline{z}=a-ib$$
#### Osservazione: $\large|z|=|\overline{z}|$
$Re(z)=Re(\overline{z})=a$
$Im(z)=-Im(\overline{z})=b$
$|z|=|\overline{z}|$=$\rho$ 
$\overline{z}=\rho[\cos(-\theta)+i\sin(-\theta)]=\rho e^{-i\theta}$ 
$Arg(\overline z)=2\pi-Arg(z)$
$(2\pi-Arg(z)=-\ \theta)$
![[07df121a-41cb-45ba-9dc5-66de0cfbaaa3.jpg|300]]
##### Osservazione: $\mathbb{C}$ Non è ordinato
#finire 

## Proprietà
1) $z+\overline z=(a+ib)+(a-ib)=2a=2Re(z)\in \mathbb{R}$
![[e8486692-819b-49eb-a8d6-687eb67fc34b.jpg|300]]
2) $z-\overline z=(a+ib)+(a-ib)=2ib=2iIm(z) \longrightarrow$ Numero immaginario puro
![[photo1696785653.jpeg|300]]
3) $z*\overline z =(a+ib)*(a-ib)=a^{2}-i^{2}b^{2}=a^{2}+b^{2}=\huge |z|^{2}\in\mathbb{R},|z|^{2}\geq 0$
4) $\huge\frac{z}{\overline z}$$=\frac{a+ib}{a-ib}*\frac{a+ib}{a+ib}=\frac{a^{2}+2aib+i^{2}b^{2}}{a^{2}b^{2}}=Re\biggl(\huge\frac{{a^{2}-b^{2}}}{{a^{2}+b^{2}}}$$\biggl)+\ i*Im\biggl( \huge\frac{2ab}{a^{2}+b^{2}}$$\biggl)$ 
###### Osservazione $\huge\frac{\overline z}{z}$:
$\huge\frac{\overline z}{z}=$$Re\biggl(\huge\frac{{a^{2}-b^{2}}}{{a^{2}+b^{2}}}$$\biggl)-\ i*Im\biggl( \huge\frac{2ab}{a^{2}+b^{2}}$$\biggl)$ 
$\huge\frac{\overline z}{z}*\frac{\overline z}{\overline z}$=$\huge\frac{\overline z^{2}}{|z|^{2}}$
$\huge\frac{\overline z}{z}*\frac{z}{z}$=$\huge\frac{z^{2}}{|z|^{2}}$
##### 5) Disuguaglianza Triangolare
$$\forall z,w \in \mathbb{C}\qquad |z+w|\leq|z|+|w|$$
##### Dimostrazione
#finire 
#### Radice di un numero complesso
Si dire radice n-esima di un numero complesso $w \in \mathbb{C}$ quel numero $z \in \mathbb{C}$ tale che: $z^{n}=w$
##### Teorema: Numero radici complesse
Sia $w \in \mathbb{C},w \not= 0$ e sia $n \in \mathbb{N}-\{0\}$: $$w=\gamma(\cos \alpha + i \sin \alpha )$$ Esistono esattamente $n$ radici n-esime complesse di $w$, $z_{0},z_{1},...,z_{n-1}$ così definite: $$z_{k}={\rho}_{k}[\cos\theta _{k}+i\sin\theta _{k}]\qquad dove\quad \begin{matrix}
\rho _k = \sqrt[n]{\gamma} \\
\theta _k= \frac{\alpha+2k\pi}{n}\quad k=0,1,..,n-1
\end{matrix}$$
###### Dimostrazione
#finire 
###### Osservazione le radici $z_{k}$ n-esime si dispongono in una circonferenza di raggio $\rho _k= \sqrt[n]{\gamma}$ come vertici di un poligono regolare iscritto.
$\theta _k-\theta_{k-1}=\frac{\alpha+2k\pi}{n}-\frac{\alpha+2(k-1)\pi}{n}=\huge \frac{2\pi}{b}\quad costante$
# Teorema fondamentale dellalgebra
![[Teorema fondamentale dell'algebra]]