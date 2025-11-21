# Sexa $X$ un $\mathbb{F}$-espazo de Banach e $T\in\mathcal{LB}(X)$ un isomorfismo.

## Apartado a) Sexa $\lambda\in\mathbb{F}\setminus\{0\}$. Demostra que $\lambda\in\rho(T)$ se e só se $\lambda^{-1}\in\rho(T^{-1})$ e, en tal caso, $$R_{T^{-1}}(\lambda^{-1})=-\lambda TR_{T}(\lambda)$$
Basta ver a implicación cara un lado, xa que $T$ isomorfismo $\iff T^{-1}$ isomorfismo e $(\lambda^{-1})^{-1}=\lambda$ e $(T^{-1})^{-1}=T$.

$\lambda\in\rho(T)\iff \lambda\id-T$ é invertible. Sexa $S:=(\lambda\id-T)^{-1}$. Vexamos que $\lambda^{-1}\id-T^{-1}$ é invertible.$$-\lambda T(\lambda^{-1}\id-T^{-1})=-T+\lambda\id=(\lambda^{-1}\id-T^{-1})(-\lambda T)$$
Como o lado central é invertible, os dous operadores do lado esquerdo e dereito tamén, así que $\lambda^{-1}\in\rho(T^{-1})$.

Ademais, $$-\lambda TS(\lambda^{-1}\id-T^{-1})=S(-\lambda T)(\lambda^{-1}\id-T^{-1})=S(\lambda\id-T)=\id=(\lambda\id-T)S=(\lambda^{-1}\id-T^{-1})(-\lambda TS)$$ Polo que $R_{T^{-1}}(\lambda^{-1})=-\lambda TR_{T}(\lambda)$.
## Apartado b) Demostra que $\sigma(T)\subset B_{\mathbb{F}}[0,\lvert\lvert T\rvert\rvert]\setminus B_{\mathbb{F}}(0,\lvert\lvert T^{-1}\rvert\rvert^{-1})$

Sabemos que $\sigma(T)\subset B_{\mathbb{F}}[0,\lvert\lvert T\rvert\rvert]$. Se $\lambda\in B_{\mathbb{F}}(0,\lvert\lvert T^{-1}\rvert\rvert^{-1})$, como $T$ isomorfismo, $\lambda\neq0$ e $\lvert\lambda^{-1}\rvert>\lvert\lvert T^{-1}\rvert\rvert\Rightarrow \lambda^{-1}\in\rho(T^{-1})\iff\lambda\in\rho(T)$. 

Así, $\sigma(T)=\sigma(T)\setminus B_{\mathbb{F}}(0,\lvert\lvert T^{-1}\rvert\rvert^{-1})\subset B_{\mathbb{F}}[0,\lvert\lvert T\rvert\rvert]\setminus B_{\mathbb{F}}(0,\lvert\lvert T^{-1}\rvert\rvert^{-1})$.