# Sexa $X=\mathcal{B}(\mathbb{R},\mathbb{R}),E,O,\id\in\mathcal{LB}(X)$ dados por $\id f=f$, $$(Ef)(x)=\frac{f(x)+f(-x)}{2}, (Of)(x)=\frac{f(x)-f(-x)}{2},$$ para $f\in X,x\in\mathbb{R}$.

## Apartado a) Demostra que $E^{2}=E$, $E+O=\id$,  $EO=OE=0$. 

$$E^{2}f(x)=E\left(\frac{f(x)+f(-x)}{2}\right)=\frac{Ef(x)+Ef(-x)}{2}=\frac{\frac{f(x)+f(-x)}{2}+\frac{f(-x)+f(x)}{2}}{2}=\frac{f(x)+f(-x)}{2}=Ef(x)\Rightarrow E^{2}=E$$

$$(E+O)f(x)=)=\frac{f(x)+f(-x)}{2}+\frac{f(x)-f(-x)}{2}=f(x)=\id f(x)\Rightarrow E+O=\id$$

$$EOf(x)=E\left(\frac{f(x)-f(-x)}{2}\right)=\frac{Ef(x)-Ef(-x)}{2}=\frac{\frac{f(x)+f(-x)}{2}-\frac{f(-x)+f(x)}{2}}{2}=0\Rightarrow EO=0$$
$$OEf(x)=O\left(\frac{f(x)+f(-x)}{2}\right)=\frac{Of(x)+Of(-x)}{2}=\frac{\frac{f(x)-f(-x)}{2}+\frac{f(-x)-f(x)}{2}}{2}=0\Rightarrow OE=0$$
## Apartado b) Calcula o espectro e a función resolvente de  $E$. 

Podemos descompoñer $X=\mathcal{E}\bigoplus\mathcal{O}$, adquirindo $E$ a representación de matriz  $M=\begin{pmatrix}1&0\\0&0\end{pmatrix}$, onde queda claro que $\sigma_{p}(E)=\{0,1\}$. Como $E^{2}=E$, $E$ é alxébrico e $\sigma_{p}(E)=\sigma(E)$. Así, $\rho(E)=\mathbb{R}\setminus\{0,1\}$. Sexa $\lambda\in\rho(E)$. $R_{E}(\lambda)=(\lambda\id-E)^{-1}=\frac{1}{\lambda-1}\left(\id-\frac{1}{\lambda}O\right)$, comprobémolo: $$(\lambda\id-E)\frac{1}{\lambda-1}\left(\id-\frac{1}{\lambda}O\right)=\frac{1}{\lambda-1}(\lambda\id-E)\left(\id-\frac{1}{\lambda}O\right)=\frac{\lambda\id-O-E+EO}{\lambda-1}=\id$$ $$\frac{1}{\lambda-1}\left(\id-\frac{1}{\lambda}O\right)(\lambda\id-E)=\frac{\lambda\id-O-E+OE}{\lambda-1}=\id$$
## Apartado c) Calcula $\sin E$. 

$$\sin E=\sum_{n=0}^{\infty}\frac{(-1)^{n}E^{2n+1}}{(2n+1)!}=\sum_{n=0}^{\infty}\frac{(-1)^{n}E}{(2n+1)!}=\left(\sum_{n=0}^{\infty}\frac{(-1)^{n}}{(2n+1)!}\right)E=\sin(1)E$$