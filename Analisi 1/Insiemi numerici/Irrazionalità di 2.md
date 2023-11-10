>[!tip] Suggerimenti
> - Un qualsiasi numero naturale moltiplicato per $2$ produce un numero pari;
>- Un numero naturale pari n può essere rappresentato come $n = 2 \cdot k$, con $k$ numero naturale;
>- Se il quadrato di un numero $n$ è pari anche $n$ è pari;
>- Una frazione può essere ridotta ai minimi termini nota con un numero finito di passaggi.
>- In Logica matematica se un proposizione $P$ è vera la sua negazione è falsa e viceversa 
#### Dimostrazione
Dimostriamo per assurdo che $\sqrt{ 2 }$ è [[Numeri reali|irrazionale]], quindi assumiamo che sia [[Numeri razionali|razionale]]:
$$\sqrt{ 2 }=\frac{m}{n} \quad m,n \in \mathbb{Z}$$
Dove $\large \frac{m}{n}$ è una frazione ridotta ai minimi termini, ovvero $m$ e $n$ sono primi tra di loro (quindi non posso essere entrambi pari)

Eleviamo al quadrato entrambi i membri:
$$\frac{m^{2}}{n^{2}}=2$$
$$m^{2} = 2n^{2}$$
Questo vuole dire che $m$ è pari poiché qualsiasi numero moltiplicato per $2$ è pari. (in questo caso abbiamo $n^{2}$ moltiplicato per $2$)

Sapendo che $m$ è pari lo possiamo sostituire con $2k$ con la seguente equazione $m=2k$ così ottenendo:
$$4k^{2} = 2n^{2}$$
$$n^{2} = 2 k^{2}$$
Ma questo vuole dire che anche $n$ è pari. È assurdo poiché nella ipotesi abbiamo assunto che la frazione $\frac{m}{n}$ era ridotta ai minimi termini.