# Demostra que todo subconxunto compacto e non baleiro $K\subset\mathbb{C}$ é o espectro dalgún operador $T\in\mathcal{LB}(\ell^{2})$. 

Primeiro, vexamos que $K$ é separable. Por ser $K$ compacto, $\forall n\in\mathbb{N},\exists B_{n,k}=B(x_{n,k},\frac{1}{n}), k\in\{1,...,n\}/x_{n,k}\in K\subset\bigcup_{k=1}^{n}B_{1,k}$. $\{x_{n,k}\}_{n,k\in\mathbb{N}}\subset K$ é un subconxunto denso e numerable. Escribimos  $\{x_{n,k\in\mathbb{N}}\}=\{\lambda_{j}\}_{j\in\mathbb{N}}=A$.

Sexa $T:\ell^{2}\to\ell^{2}$ definido como $(Tx)_{n}=\lambda_{n}x_{n}$. $T$ ben definido, xa que $\sup_{n\in\mathbb{N}}\lvert\lambda_{n}\rvert<\infty$ por ser $K$ compacto e $T$ é lineal e continuo. $Te_{n}=\lambda_{n}e_{n}$, polo que $A\subset\sigma_{p}(T)$ e, como $\sigma(T)$ é compacto, $K=\overline{A}\subset\sigma(T)$.

Vexamos agora que $\mathbb{C}\setminus K\subset\rho(T)$, o que remataría a proba.

Se $\lambda\in\mathbb{C}\setminus K$, $d(\lambda,K)=:\delta>0$, polo que $\lvert\lambda-\lambda_{n}\rvert^{-1}<\delta^{-1}$, polo que $S$ definido como $(Sx)_{n}=(\lambda-\lambda_{n})x_{n}$ ben definido, lineal e continuo. Ademais, $S(\lambda\id-T)=(\lambda\id-T)S=\id$, polo que $S=R_{T}(\lambda)$ e $\lambda\in\rho(T)$.

Así, $\sigma(T)=K$.