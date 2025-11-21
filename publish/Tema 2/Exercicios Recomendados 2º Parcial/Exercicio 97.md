# Demostra, sen invocar o Teorema Fundamental da Álxebra nin o teorema de caracterización dos espazos vectoriais de dimensión finita, que todo operador lineal $T:\mathbb{C}^{n}\to\mathbb{C}^{n}$ ten un autovalor complexo.

## Paso 1: Ver que todo operador lineal é limitado.

Sexa $T:\mathbb{C}^{n}\to\mathbb{C}^{n}$ definido como $T(z_{1},...,z_{n})=\sum_{k=1}^{n}z_{k}Te_{k}$. Polo tanto, $$\lvert\lvert T(z_{1},...,z_{n})\rvert\rvert_{1}=\left\lvert\left\lvert\sum_{k=1}^{n}z_{k}Te_{k}\right\rvert\right\rvert_{1}\leq\sum_{k=1}^{n}\left\lvert z_{k}\right\rvert\left\lvert\left\lvert Te_{k}\right\rvert\right\rvert_{1}\leq \left(\max_{1\leq k\leq n}\left\lvert\left\lvert Te_{k}\right\rvert\right\rvert_{1}\right)\sum_{k=1}^{n}\left\lvert z_{k}\right\rvert=\left(\max_{1\leq k\leq n}\left\lvert\left\lvert Te_{k}\right\rvert\right\rvert_{1}\right)\lvert\lvert (z_{1},...,z_{n})\rvert\rvert_{1}$$ Polo tanto, $T$ limitado.
## Paso 2: $\sigma(T)\neq\emptyset$.

Por teoría.
## Paso 3: $\sigma(T)\subset\sigma_{p}(T)$.

Sexa $\lambda\in\sigma(T)\setminus\sigma_{p}(T)$. Entón, $G=\lambda\id-T$ non é sobre e $\dim G(\mathbb{C}^{n})<n\Rightarrow\dim G(\mathbb{C}^{n})\leq n-1$. Como $\dim\ker G+\dim G(\mathbb{C}^{n})=\dim \mathbb{C}^{n}=n$, $\dim \ker G\geq 1\Rightarrow \lambda\in\sigma_{p}(T)$, chegando a unha contradición. Así, $$\sigma(T)\setminus\sigma_{p}(T)=\emptyset\Rightarrow\sigma_{p}(T)=\sigma(T)\neq\emptyset$$.