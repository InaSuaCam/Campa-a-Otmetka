# Estuda o espectro do operador $T:\ell^{\infty}(\mathbb{R})\to\ell^{\infty}(\mathbb{R})$ dado por $(Tx)_{n}=x_{2n}$ para $(x_{k})_{k\in\mathbb{N}}\in\ell^{\infty}(\mathbb{R})$ e $n\in\mathbb{N}$.

Sexa $x\in\ell^{\infty}(\mathbb{R})$. Supoñamos que $Tx=\lambda x$. Así, $x_{2n}=\lambda x_{n}$. Supoñamos que $\lvert\lambda\rvert>1$ e vexamos que non pode ser. Como $x_{2n}=\lambda x_{n}$, $x_{2^n}=\lambda^{n} x_{1}$, que, como $\lvert\lambda\rvert>1$, diverxe a $\pm\infty$ e, polo tanto, non está en $\ell^{\infty}(\mathbb{R})$. Así, $\sigma_{p}(T)\subset [-1,1]$. Vexamos que $[-1,1]\subset\sigma_{p}(T)$.

Sexa $\lambda\in[-1,1]$ e consideremos $x_{n}=\lambda^{k}$, onde $k=\nu_{2}(n)$ (valoración $2$-ádica). Claramente, $\nu_{2}(2n)=\nu_{2}(n)+1$, polo que $x_{2n}=\lambda^{k+1}=\lambda\cdot\lambda^{k}=\lambda x_{n}$. Ademais, $\sup_{n\in\mathbb{N}}\lvert x_{n}\rvert=\sup_{n\in\mathbb{N}}\lvert \lambda^{\nu_{2}(n)}\rvert\leq\sup_{n\in\mathbb{N}}\lvert\lambda\rvert=\lvert\lambda\rvert\leq1$, polo que $(x_{n})_{n\in\mathbb{N}}\in\ell^{\infty}(\mathbb{R})$, concluíndo que $\lambda\in\sigma_{p}(T)$. Así, $\sigma_{p}(T)=[-1,1]$.

Agora, vexamos que $\sigma(T)\subset[-1,1]$ e, polo tanto, $\sigma(T)=\sigma_{p}(T)=[-1,1]$. $$\lvert\lvert Tx\rvert\rvert_{\infty}=\sup_{n\in\mathbb{N}}\lvert x_{2n}\rvert\leq\sup_{n\in\mathbb{N}}\lvert x_{n}\rvert=\lvert\lvert x\rvert\rvert_{\infty}$$ Polo que $\lvert\lvert T\rvert\rvert\leq 1\Rightarrow \sigma(T)\subset[-1,1]$.

En resumo, $\sigma(T)=[-1,1]$ e $\rho(T)=\mathbb{R}\setminus[-1,1]$.

