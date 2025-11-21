# Sexa $X$ un espazo de Banach complexo de dimensión infinita e $T\in\mathcal{LB}(X)$ un operador alxébrico de polinomio mínimo $p(x)=x^3-1$. 
## Apartado a) Demostra que o espectro puntual de $T$ coincide coas raíces de $p$.

Sexa $S=\{z\in\mathbb{C}/p(z)=0\}=\left\{1,\frac{1}{2}\pm\frac{i\sqrt{3}}{2}\right\}$. Vexamos que $\sigma_{p}(T)\subset S$. $$\lambda\in\sigma_{p}(T)\iff\exists x\in X\setminus\{0\}/ Tx=\lambda x\Rightarrow (T^{3}-\id)x=0\iff (\lambda^{3}-1)x=0\iff p(\lambda)=\lambda^{3}-1=0\Rightarrow \lambda\in S$$ 
Vexamos que $S\subset \sigma_{p}(T)$. Sexa $\lambda\in S$ e supoñamos que $\lambda\notin\sigma_{p}(T)$. Sabemos que $T^{3}x-x=0,\forall x\in X$, e que $Tx-\lambda x\neq0,\forall x\in X$. Vexamos entón que $q(z)=\frac{p(z)}{z-\lambda}$ é un polinomio anulador de $T$, chegando a contradición.

$$q(T)x=\frac{p(T)x}{(T-\lambda\id)x}=0,\forall x\in X$$
Polo que $q$ polinomio anulador de $T$ e $p$ non é mínimo ($\deg q < \deg p$), chegandoa contradición, polo que $\lambda\in\sigma_{p}(T)$ e $S=\sigma_{p}(T)$.

## Apartado b) Calcula as proxeccións de $T$ sobre cada un dos autoespazos de $T$.

$X=\mathcal{E}_{1}\bigoplus\mathcal{E}_{\frac{1}{2}+\frac{i\sqrt{3}}{2}}\bigoplus\mathcal{E}_{\frac{1}{2}-\frac{i\sqrt{3}}{2}}$     

$T|_{\mathcal{E}_{\lambda}}=\lambda\id$ e $T=\begin{pmatrix}1&0&0\\0&\frac{1}{2}+\frac{i\sqrt{3}}{2}&0\\0&0&\frac{1}{2}-\frac{i\sqrt{3}}{2}\end{pmatrix}$.

Realmente non sei ao que se refire neste apartado, polo que probablemente estea mal.
## Apartado c) Comproba que os autoespazos son ortogonais dous a dous.

Sexan $x\in\mathcal{E}_{\lambda}$ e $y\in\mathcal{E}_{\mu}$. $$\langle x,y\rangle=...=0$$

## Apartado d) Calcula o espectro de $T$ e xustifica a resposta.

Por ser $T$ alxébrico, $\sigma(T)=\sigma_{p}(T)=S$.

## Apartado e) É $T$ compacto? Xustifica a resposta.

Non. Se $T$ fose compacto, $0\in\sigma(T)=\sigma_{p}(T)=S$, pero $p(0)=0^{3}-1=-1\neq 0$.

## Apartado f) Calcula un operador $S$ tal que $e^{S}=T$.

Polo apartado b), só temos que calcular un logaritmo dos autovalores. Así, $S=\begin{pmatrix}0&0&0\\0&\frac{i\pi}{3}&0\\0&0&-\frac{i\pi}{3}\end{pmatrix}$ se descompoñemos $X$ nos autoespazos de $T$.