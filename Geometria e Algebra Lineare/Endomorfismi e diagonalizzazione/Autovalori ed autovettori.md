#### Definizione
Un applicazione lineare $f: V \to V$ si dice endomorfismo e $hom(V,V) = end(v)$
Un endomorfismo invertibile si dice automorfismo.

L’insieme di tutti gli automobilismi di $V$ si dice $GL(V)$
Gruppo lineare generale sse $V$



>[!example] Esempio
> $$g: \mathbb{R}[x]_{2} \to \mathbb{R}[x]_{2} \quad g(P) = Id(P(x)) \to \frac{d^{2}}{dx^{2}} (P(x))$$
> $$P(x) = x^{2} \to g(P) = x^{2} + 2 \quad f:\mathbb{R}[x]_{2} \to \mathbb{R}[x]_{2}$$
$$P(x) \to \frac{d}{dx} P(x)$$
$$f^{0} = I’d \quad f^{2} = \frac{d^{2}}{dx^{2}} \to g=f^{0}+f^{2} = 1 \cdot f^{0} + 0 \cdot f^{1} + 1 \cdot f^{2}$$
$$[g]_{B} = 1 [f^{0}]_{B} + 0 \cdot [f^{1}]_{B} + 1 \cdot [f^{2}]_{B}$$


## Autovalori ed autovettori

#### Definizione
$\underline{v} \in V \setminus \{ \underline{0} \}$ è autovettore di $f \in end(V)$ se esiste $\lambda \in \mathbb{K}$ tale che $f(\underline{v}) = \lambda \underline{v}$
Lo scalare $\lambda$ è detto auto valore associato all’autovettore $\underline{v}$

Un vettore, se viene semplicemente riscalato dall’[[Applicazioni lineari|applicazione lineare]] allora si definisce autovettori di $f_{A}$

>[!example] Esempio
> $$V = \mat(2,1;\mathbb{R}) \quad A =[\begin{matrix}
> 2 & 3 \\ \\
> -1 & -2 \\
> \end{matrix}] f_{A} : V\to V \quad$$
>[!example] Esempio
> $$V = \mat(2,1;\mathbb{R}) \quad A =[\begin{matrix}
> 2 & 3 \\ \\
> -1 & -2 \\
> \end{matrix}] f_{A} : V\to V \quad$$
> finire di copiare da esercizio A3478

## Applicazione diagonalizzabile

#### Definizione 6.4
Un’applicazione $f \in end(v)$ è detta diagonalizzabile se esiste una base $B$ di $V$ composta da autovettori di $f$.

 >[!example] Esempio
> $$Id_{v} : V \to V \quad (\underline{v} \to \underline{v}) \to Id_{v}(\underline{v}) = 1 \cdot \underline{v} \to \forall \underline{v} \in V \quad \text{è autovettore di } Id_{v}$$

## Primo criterio di diagonalizzabilità (Teorema 6.5)
Sia $V$ [[Spazi vettoriali|spazio vettoriale]] finitamente generato su campo $\mathbb{K}$ e sia $f \in end(V)$.
Allora $f$ è diagonalizzabile se e solo se esiste una base $B$ di $V$ tale che la matrice rappresentativa $[f]_{B}$ è diagonale.

#### Dimostrazione
Sia $f$ diagonalizata $\to$ esiste $B=(\underline{v_{1}},\dots,\underline{v_{n}})$ base di autovettori
$$\to [f]_{B} =[[f(\underline{v_{1}})]_{B} \dots [f(\underline{v_{n}})]_{B}] =[[\lambda)_{1} \cdot v_{1}]_{B} \dots [\lambda_{n} \cdot \underline{v_{n}}]]$$
$$=\left[ \begin{matrix}
\lambda_{1} & \dots & 0  \\
\vdots & \ddots & \vdots  \\
0 & \dots & \lambda_{n}
\end{matrix}\right]$$

## Autospazio

#### Definizione 6.8
Se $\lambda$ è autovalore di $f$, allora l’insieme $V_{\lambda} = \{ \underline{v} \in V | f(\underline{v}) = \lambda \cdot \underline{v} \}$
Si chiama autospazio di $f$ associato a $\lambda$

>[!info] Osservazione
> $$V_{\lambda} = \{ \text{autovettori associati a } \lambda \} \cup \{ \underline{0} \} \neq \{ \underline{0} \}$$

#### Propsizione 6.9
$V_{\lambda}$ è un sotto spazio di $V$ soddisfacente $\dim(V_{\lambda}) \geq 1$

##### Dimostrazione
$$\underline{v} \in V_{\lambda} \text{ sse } f(\underline{v}) = \lambda \cdot \underline{v}$$
$$\text{sse} \quad f(\underline{v})- \lambda \cdot \underline{v} = \underline{0}$$
$$\text{sse} \quad f(\underline{v}) = - \lambda \cdot Id_{v}(\underline{v}) = \underline{0}$$
$$\text{sse} (f - \lambda \cdot Id_{v})(\underline{v}) = \underline{0}$$
Cioè $\underline{v} \in V_{\lambda}$ sse $\underline{v} \in \ker(f-\lambda \cdot Id_{v})$. Cioè $V_{\lambda} = \ker(f- \lambda \cdot Id_{v})$
Di conseguenza $V_{\lambda}$ è sottospazio vettoriale

#### Lemma 6.30
Sia $V$ uno spazio vettoriale su campo $\mathbb{K}$ e sia $f $


## Similitudine e polinomio caratteristico

#### Definizione matrici simili
Data $A,B \in \mat(n,\mathbb{K})$, $B$ si dice simile ad $A$ se esiste una matrice $S\in GL(n;\mathbb{K})$ tale che $B = S^{-1} A S$

>[!example] Esempio fondamentale
> $$[f]_{B} \ \text{ e } \ [f]_{B^{1}} \quad \text{ sono simili:}$$
> $$[f]_{B^{1}} = M_{BB^{1}} * [f]_{B} * M_{B^{1}B} = \underbrace{ (M_{B^{1}B})^{-1} }_{ S^{-1} } * [f]_{B} * \underbrace{ M_{B^{1}B} }_{ S }$$

## Criterio di diagonalizzabilità (prop 6.17)

$f \in end(V)$ è diagonalizzabile se e solo se la matrice $[f]_{B}$ è simile ad una matrice diagonale $D$, ovvero  se e solo se esiste una matrice diagonalizzante $S$ tale che $S^{-1} [f]_{B} S = D$
Data $B^{1}$ base di autovettori $\to S = M_{B^{-1}B}$

#### Proposizione 6.11
La similitudine è una [[Relazioni di equivalenza ed insieme quoziente|relazione di equivalenza]] $R$.

##### Dimostrazione
- Riflessività $A \sim^{\mathrm{Im}} A : A = \mathrm{Im}^{-1} A \mathrm{Im}$
- Simmetria: sia $B \sim^{S} A \to B = S^{-1}AS\to SBS^{-1}=S(S^{-1}AS)S^{-1}=(SS^{-1}) A (SS^{-1})=\mathrm{Im}A\mathrm{Im}=A \to A \sim^{S^{-1}}B;$
-  Transitività: siano $A \sim^{S} B, B \sim^{T} C \to A =S^{-1}BS, B=T^{-1}CT \to A = S^{-1}(T^{-1}CT)S=(S^{-1}T^{-1})C(TS)=(TS)^{-1}C(TS)\to A \sim^{TS} C$

Ad ogni $f$ corrisponde una sola classe di matrici simili che rappresentano $f$ rispetto a tutte le possibili basi.
$f$ è diagonalizzabile sse all’interno della classe di matrici rappresentative esiste una matrice diagonale.
