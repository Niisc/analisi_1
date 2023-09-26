#lezione1
###### Definizione
Siano $a_1, a_2, . . . ,a_n$ $n$ numeri reali. La loro somma: $a_1+a_2+...a_n$ si può indicare in forma compatta col simbolo sommatoria:
$$\sum_{i\in I}ai$$
*i* indice
**I** famiglia
ai $\in$ $R$ 
## Proprietà
##### 1) Indice muto
$$\sum_{i\in I}^nai=\sum_{j  \in J}^naj \qquad I=J$$
##### 2) Traslazione di indici
$$\sum_{i=1}^na_i=\sum_{i=1+m}^{n+m} a_{i-m}$$
##### 3) Riflessione di indici
$$\sum_{i=1}^na_i=\sum_{i=1}^{n} a_{n-i+1}=\sum_{i=0}^{n-1} a_{n-i}$$
##### 4) Prodotto per costante $c\not=0$ (Proprietà distributiva)
$$\sum_{i\in I}^nca_i=c\sum_{i\in I}^na_i$$
##### 5) Somma di sommatorie con stessi indici:
$$\sum_{i\in I}^nai+\sum_{i\in I}^nbi=\sum_{i\in I}^n(a_i+b_i)$$
**La sommatoria con stessi indici è un [[Operatore Lineare]]**
##### 6) Sommatoria con termini costanti 
$$ai=k \qquad \sum_{i\in I}k=(\#I)*k$$
$I$ è la famiglia di indici quindi la sommatoria con termini costanti non è altro che il prodotto tra i termini costanti e la cardinalità di $I$
##### 7) Scomposizione di una sommatoria
$$\sum_{i=1}^na_i=\sum_{i=1}^ka_i+\sum_{i=1+k}^{n}a_i\qquad k<n$$![[73e7c6d7-88c3-493e-aa25-ba17c5be0735.jpg|200]]
##### 8) Sommatorie con più indici
$$\sum_{i,j}^na_{i,j}=\sum_{j \in J}^n\biggl(\sum_{i \in I}^{n}a_{i,j}\biggl)$$
Posso separare le due sommatorie e svolgere prima una e poi l'altra:
$$\sum_{j \in J}^n\biggl(\sum_{i \in I}^{n}a_{i,j}\biggl)=\sum_{j \in J}^n\biggl(a_0,j+a_1,j...\biggl)$$   
### Binomio di Newton
$$(a+b)^n=\sum_{k=0}^n {n \choose k}a^kb^{n-k}$$
${x \choose k}$  [[Fattoriale#Coefficiente Binomiale]]

ex $$(a+b)^8 = \sum_{k=0}^8{8 \choose k}a^kb^{8-k}$$
$$={8 \choose 0}a^0b^8+{8\choose 1}a^1b^7+....+{8\choose8}a^8b^0$$
(ricavabili anche con il triangolo di Tartaglia)
**Dimostrato con il [[! Principio di induzione]]**
