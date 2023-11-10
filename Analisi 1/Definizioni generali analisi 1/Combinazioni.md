#### Formula
$${n \choose k}={n! \over k!(n-k)!}\qquad 0\leq k \leq n$$
Dove $!$ è [[Fattoriale]]

#### Proprietà
1) $${n+1 \choose k} = {n \choose k-1} + {n \choose k}$$
#### Dimostrazione
1) $${\frac{(n+1)!}{k!(n+1-k)!}}=\frac{n!}{(k-1)!(n-k+1)!}+ \frac{n!}{k!(n-k)!}=$$
$$={\frac{(n+1)!}{k!(n+1-k)!}}=\frac{{k!(n-k)!n!+n!(k-1)!(n-k+1)!}}{(k-1)!(n-k+1)!k!(n-k)!}=$$
$$=\frac{({k!(n-k)!+(k-1)!(n-k+1)!})n!}{(k-1)!(n-k+1)!k!(n-k)!}=$$
$$=\frac{({\cancel{ k+ }(n\cancel{ -k }+1)})n!\cancel{ (k-1)! }\cancel{ (n-k)! }}{\cancel{ (k-1)! }(n-k+1)!k!\cancel{ (n-k)! }}=$$
$$=\frac{(n+1)n!}{(n-k+1)!k!}={\frac{(n+1)!}{k!(n+1-k)!}}$$
