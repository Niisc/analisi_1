#lezione3
$$\mathbb{N}\subseteq \mathbb{Z} \subseteq \mathbb{Q} \subseteq \mathbb{R} \quad Insiemi \quad infiniti$$
### Corrispondenza Biunivoca

Stabilire quale degli insiemi sia il più "*numeroso*":
Due insiemi $A,B$ si dicono di *uguale [[Insiemi#Cardinalità|cardinalità]]* se possono essere messi in corrispondenza biunivoca tra loro, cioè se esiste una legge che associa ad ogni elemento di A uno e uno solo di B e viceversa.

>[!info] Osservazione
>Confronto, non conto

Identifichiamo l'idea di uguale numerosità con una *corrispondenza biunivoca*:
$\mathbb{N}=\{0,1,2,3,...\}\quad \mathbb{N}_2=\{2,3,4,5...\}$
corrispondenza biunivoca $n\rightarrow n+2$ 
$\mathbb{N}=\{0,1,2,3,...\}\quad \mathbb{Z}=\{...-2,-1,0,1;2...\}$
corrispondenza biunivoca $2n\rightarrow -n$ (ai numeri pari associo i negativi), $2n-1\rightarrow n$ (ai numeri dispari associo i numeri positivi)
### Esiste una corrispondenza biunivoca fra un insieme e un suo sottoinsieme proprio

1) Un insieme A si dice **infinito** se un suo sottoinsieme **proprio** ha la stessa cardinalità di A:
$B\subset A$  con $B\not=A$, $B\not=\emptyset$ : $|A|=|B|$  $\leftarrow$  Corrispondenza biunivoca fra A e B

2) Un insieme A si dice **Numerabile** se ha la stessa **cardinalità** di $\mathbb{N}$ ([[Numeri naturali]]). Esiste $f:N\rightarrow A$ corrispondenza biunivoca

$\mathbb{Z}$ ([[Numeri interi]]) è un insieme infinito numerabile
$\mathbb{Q}$ ([[Numeri razionali]]) è un insieme infinito numerabile

##### Teorema di Cantor
Costruisco una corrispondenza biunivoca fra $N$ e $Q$ : 
$\mathbb{Q}^+ =\{{m \over n}\quad | \quad m,n \in N, n\not= 0 \}$   

Considero $m+n$:
$m+n=1\qquad {0 \over 1}=0$
$m+n=2\qquad {1 \over 1} \quad {0 \over 2}(!)=0$ Già considerato 
$m+n=3\qquad {1 \over 2} \quad {2 \over 1}$
$\dots$

![[c03b8e87-fdce-410b-a026-0b65f1a06f14.jpg]]
Quindi sì ha una corrispondenza biunivoca:
$f:N\longmapsto Q$ 
$f(0)=0,f(a_n)=x_n,f(a_n-1)=-x_n$ $\qquad\leftarrow\qquad Q$ è numerabile  
$\mathbb{R}$ (insieme reali) è un insieme infinito **NON** numerabile