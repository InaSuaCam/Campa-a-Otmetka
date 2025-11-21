# Consideremos o *operador diferenza* dado por $\Delta:\ell^{\infty}(\mathbb{C})\to\ell^{\infty}(\mathbb{C})$ tal que $$\Delta(x_{n})_{n\in\mathbb{N}}=(x_{n+1}-x_{n})_{n\in\mathbb{N}}$$
## Apartado a) Demostra que $\Delta$ está ben definido, é lineal e continuo.

$$\lvert\lvert\Delta(x_{n})_{n\in\mathbb{N}}\rvert\rvert_{\infty}=\lvert\lvert(x_{n+1}-x_{n})_{n\in\mathbb{N}}\rvert\rvert_{\infty}\leq\lvert\lvert(x_{n+1})_{n\in\mathbb{N}}\rvert\rvert_{\infty}+\lvert\lvert(x_{n})_{n\in\mathbb{N}}\rvert\rvert_{\infty}\leq2\lvert\lvert(x_{n})_{n\in\mathbb{N}}\rvert\rvert_{\infty}$$

Isto proba que $\Delta$ ben definido, xa que $\Delta(x_{n})_{n\in\mathbb{N}}$ ten norma infinito finita se $(x_{n})_{n\in\mathbb{N}}$ tamén a ten. Se vemos que é lineal, isto tamén probaría que é continuo, por ser un operador limitado.

Sexan $(x_{n})_{n\in\mathbb{N}},(y_{n})_{n\in\mathbb{N}}\in\ell^{\infty}(\mathbb{C})$ e $\lambda\in\mathbb{C}$.
$$\Delta\left((x_{n})_{n\in\mathbb{N}}+\lambda(y_{n})_{n\in\mathbb{N}}\right)=\Delta(x_{n}+\lambda y_{n})_{n\in\mathbb{N}}=(x_{n+1}+\lambda y_{n+1}-x_{n}-\lambda y_{n})_{n\in\mathbb{N}}=(x_{n+1}-x_{n})_{n\in\mathbb{N}}+(x_{n+1}-x_{n})_{n\in\mathbb{N}}+\lambda(y_{n+1}-y_{n})_{n\in\mathbb{N}}=\Delta(x_{n})_{n\in\mathbb{N}}+\lambda\Delta(y_{n})_{n\in\mathbb{N}}$$
Así, $\Delta$ lineal e continuo.

## Apartado b) Calcula a norma de $\Delta$.

Como vimos antes, $\lvert\lvert\Delta\rvert\rvert\leq 2$. Vexamos que $\lvert\lvert\Delta\rvert\rvert=2$. Consideremos $x_{n}=(-1)^{n}$.

$$\lvert\lvert\Delta(x_{n})_{n\in\mathbb{N}}\rvert\rvert_{\infty}=\sup_{n\in\mathbb{N}}\lvert(-1)^{n+1}-(-1)^{n}\rvert=\sup_{n\in\mathbb{N}}2=2=2\lvert\lvert(x_{n})_{n\in\mathbb{N}}\rvert\rvert$$

## Apartado c) Compruebe que $\Delta(c_{0})\subset c_{0}.$

Putamente trivial, se vai a 0, como o límite é lineal, a diferenza tamén vai a 0.

## Apartado d) Calcula o espectro puntual de $\Delta$.

Se $\lambda\in\sigma_{p}(\Delta)$, $x_{n+1}-x_{n}=\lambda x_{n}\forall n\in\mathbb{N}$. Así, $x_{n+1}=(\lambda+1)x_{n}$ e $x_{n}=(\lambda+1)^{n}x_{0}$, que está en $\ell^{\infty}(\mathbb{C})$ se e só se $\lvert\lambda+1\rvert\leq1$. Así, $\sigma_{p}(\Delta)=B_{\mathbb{C}}[-1,1]$.

## Apartado e) Calcula o espectro puntual da función $\tilde{\Delta}=\Delta|_{c_{0}}:c_{0}\to c_{0}$.

Obviamente, $\sigma_{p}(\tilde{\Delta})\subset\sigma_{p}(\Delta)$. Dos autovectores de $\Delta$, os que están en $c_{0}$ son tales que $\lvert\lambda+1\rvert<1$, polo que $\sigma_{p}(\tilde{\Delta})=B_{\mathbb{C}}(-1,1)$.