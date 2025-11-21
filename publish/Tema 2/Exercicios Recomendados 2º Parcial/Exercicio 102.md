# Calcula unha raíz cadrada do operador $T:\mathcal{BC}(\mathbb{C},\mathbb{C})\to\mathcal{BC}(\mathbb{C},\mathbb{C})$ tal que $(Tf)(z)=e^{\frac{2}{3}\pi iz}f(-z)$ para toda $f\in\mathcal{BC}(\mathbb{C},\mathbb{C})$.

Observemos que $T^{2}=\id$. $(T^{2}f)(z)=T\left(e^{\frac{2}{3}\pi iz}f(-z)\right)=e^{\frac{2}{3}\pi iz}e^{-\frac{2}{3}\pi iz}f(z)=f(z)$. Así, $\mathcal{BC}(\mathbb{C},\mathbb{C})=Y\bigoplus Z=\ker(\id-T)\bigoplus\ker(-\id-T)$.

$P_{Y}=\frac{\id+T}{2}$ e $P_{Z}=\frac{\id-T}{2}$ son as proxeccións asociadas e $T$ ten matriz $\begin{pmatrix}1&0\\0&-1\end{pmatrix}$, polo que se $S$ con matriz $\begin{pmatrix}1&0\\0&i\end{pmatrix}$ na mesma descomposición é unha raíz cadrada de $T$.

$S=P_{Y}+iP_{Z}=\frac{1+i}{2}\id+\frac{1-i}{2}T$ e é trivial comprobar que $S^{2}=T$.