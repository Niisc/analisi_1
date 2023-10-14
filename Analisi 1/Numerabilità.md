#lezione3
$$\mathbb{N}\subseteq \mathbb{Z} \subseteq \mathbb{Q} \subseteq \mathbb{R} \quad Insiemi \quad infiniti$$

### Corrispondenza Biunivoca

Stabilire quale degli insiemi sia il più "*numeroso*":
Due insiemi A,B si dicono di *uguale cardinalità* (traducibile in numerosità) se possono essere messi in corrispondenza biunivoca tra loro, cioè se esiste una legge che associa ad ogni elemento di A uno e uno solo di B e viceversa.

- (confronto, non conto)
Identifichiamo l'idea di uguale numerosità con una *corrispondenza biunivoca*:
 ###### $N=\{0,1,2,3,...\}\quad N_2=\{2,3,4,5...\}$
corrispondenza biunivoca $n\rightarrow n+2$ 
###### $N=\{0,1,2,3,...\}\quad Z=\{...-2,-1,0,1;2...\}$
corrispondenza biunivoca $2n\rightarrow -n$ (ai numeri pari associo i negativi), $2n-1\rightarrow n$ (ai numeri dispari associo i numeri positivi)
### Esiste una corrispondenza biunivoca fra un insieme e un suo sottoinsieme proprio
#### Un insieme A si dice **infinito** se un suo sottoinsieme **proprio** ha la stessa cardinalità di A:
$B\subset A$  con $B\not=A$, $B\not=\emptyset$ : $|A|=|B|$  $\leftarrow$  Corrispondenza biunivoca fra A e B
##### Un insieme A si dice **Numerabile** se ha la stessa **cardinalità** di $N$ ([[! Numeri Naturali]]).Esiste $f:N\rightarrow A$ corrispondenza biunivoca
$Z$ (insieme interi)è un insieme infinito numerabile
$Q$ (insieme razionale) è un insieme infinito numerabile
	**Teorema di Cantor**
			Costruisco una corrispondenza biunivoca fra $N$ e $Q$ : 
				- $Q^+ =\{{m \over n}\quad | \quad m,n \in N, n\not= 0 \}$   
			- Considero m+n:
				$m+n=1\qquad {0 \over 1}=0$
				$m+n=2\qquad {1 \over 1} \quad {0 \over 2}(!)=0$ Già considerato 
				$m+n=3\qquad {1 \over 2} \quad {2 \over 1}$
				....
			![[c03b8e87-fdce-410b-a026-0b65f1a06f14.jpg]]
			Quindi sì ha una corrispondenza biunivoca:
				$f:N\longmapsto Q$ 
				 $f(0)=0,f(a_n)=x_n,f(a_n-1)=-x_n$ $\qquad\leftarrow\qquad Q$ è numerabile  
	- $R$ (insieme reali) è un insieme infinito **NON** numerabile
		- **Teorema di Cantor**