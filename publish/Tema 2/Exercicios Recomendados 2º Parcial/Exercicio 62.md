# Sexa $X$ un espazo de Banach. Demostra que
## Apartado a) Se $P:X\to X$ é unha proxección continua, $P(X)$ e $(\id-P)(X)$ son subespazos pechados  de $X$.

Basta comprobalo para $P(X)$, xa que, se $P$ é unha proxección, $(\id-P)^2=\id-2P+P^2=\id-P$ e $\id-P$ tamén é unha proxección.

Como $P(X)=\ker (\id-P)=(\id-P)^{-1}(\{0\})$ e $\{0\}$ é pechado, $P(X)$ é pechado.

## Apartado b) Se $X=U\bigoplus V$ e $U$ e $V$ son subespazos pechados, a proxección $P$ sobre $U$ é continua.

Recordemos a definición de $P$. Se $x=u+v$, (descomposición dada pola suma directa) $Px=u$. Observemos que $P=\pi_{1}\circ\iota$, con $\iota:X\to U\times V$ tal que $\iota x=(u,v)$ e $\pi_{1}$ a proxección na primeira compoñente. Como $\pi_{1}$ é continua, basta ver que $\iota$ é continua.

$\lvert\lvert \iota x\rvert\rvert=\max\{\lvert\lvert u\rvert\rvert, \lvert\lvert v\rvert\rvert\}\leq \lvert\lvert x\rvert\rvert$, polo que $\iota$ é continua e $P$ tamén.

## Apartado c) Se $X$ e un espazo de dimensión infinita, existe unha proxección $P:X\to X$ que non é continua.

Sexan $B$ unha base de Hamel de $X$ e $\tilde{B}\subset B$ numerable. A proxección sobre $U=\langle \tilde{B} \rangle$ non é continua, xa que, se o fose, $U$ sería pechado e, polo tanto, de Banach, o que non pode ser, porque non hai espazos de Banach con bases de Hamel infinito numerables.

