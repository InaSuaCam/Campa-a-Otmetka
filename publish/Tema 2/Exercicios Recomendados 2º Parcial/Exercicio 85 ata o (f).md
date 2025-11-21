# Sexan $n\in\mathbb{Z}^+$, $[a,b]\subset\mathbb{R}$, $g_{k}\in L^{2}([a,b],\mathbb{F})$ para $k=1,...,n$. Supoñamos que $\langle g_{k},g_{j} \rangle=\delta_{j}^{k}$ para calquera $j,k=1,...,n$. Sexa $K(t,s)=\sum_{j,k=1}^{n}\alpha_{j,k}g_{j}(t)\overline{g_{k}(s)}$ para $t,s\in[a,b]$, onde $a_{j,k}\in\mathbb{F}$ para $j,k=1,...,n$.
## Apartado a) Demostra que $K\in L^{2}([a,b]^{2},\mathbb{F})$.

$$\int_{[a,b]^{2}}\lvert K(t,s)\rvert^{2}\,\text{d}(t,s)=\int_{a}^{b}\int_{a}^{b} \left\lvert\sum_{j,k,l,m=1}^{n}\alpha_{j,k}\alpha_{l,m}g_{j}(t)\overline{g_{l}(s)}g_{l}(t)\overline{g_{m}(s)}\right\rvert \,\text{d}t\,\text{d}s\leq \sum_{j,k,l,m=1}^{n}\lvert \alpha_{j,k}\alpha_{l,m}\rvert\int_{a}^{b}\int_{a}^{b} \left\lvert g_{j}(t)g_{l}(t) \right\rvert \left\lvert \overline{g_{k}(s)g_{m}(s)} \right\rvert \,\text{d}t\,\text{d}s=\sum_{j,k,l,m=1}^{n}\lvert \alpha_{j,k}\alpha_{l,m}\rvert \int_{a}^{b} \left\lvert g_{j}(t)g_{l}(t) \right\rvert \,\text{d}t \int_{a}^{b} \left\lvert \overline{g_{k}(s)g_{m}(s)} \right\rvert \,\text{d}s<\infty$$ 
Sendo a última desigualdade porque o produto de funcións de $L^2$ está en $L^1$ e é unha suma finita de números reais.

## Apartado b) Demostra que $T\in\mathcal{LK}\left(L^{2}([a,b],\mathbb{F}),L^{2}([a,b],\mathbb{F})\right)$, onde $Tf(t)=\int_{a}^{b}K(t,s)f(s)\,\text{d}s$.

Vexamos que $T$ ben definido. En realidade, basta ver que $Tf\in L^{1}([a,b],\mathbb{F})\subset L^{2}([a,b],\mathbb{F})$, porque $\mu\left([a,b]\right)=b-a<\infty$.

$$\int_{a}^{b}Tf(t)\,\text{d}t=\int_{a}^{b}\int_{a}^{b}K(t,s)f(s)\,\text{d}s\,\text{d}t$$
Como $K,g\in L^{2}([a,b]^{2},\mathbb{F})$, con $g(t,s)=f(s)$, o seu produto está en $L^{1}\subset L^{2}$ e o lado dereito da igualdade é finito, polo que o lado esquerdo tamén e $T$ ben definido.

Vexamos que $T$ é continuo. $$\lvert\lvert Tf\rvert\rvert=\sqrt{\int_{a}^{b}Tf(t)^{2}\,\text{d}t}=\sqrt{\int_{a}^{b}\left(\int_{a}^{b}K(t,s)f(s)\,\text{d}s\right)^{2}\,\text{d}t}=\sqrt{\int_{a}^{b}\left\langle K(t,\cdot),f\right\rangle^{2}\,\text{d}t}\leq\sqrt{\int_{a}^{b} \lvert\lvert K(t,\cdot)\rvert\rvert^{2} \lvert\lvert f\rvert\rvert^{2}\,\text{d}t}=\lvert\lvert K\rvert\rvert\cdot\lvert\lvert f\rvert\rvert$$

Trivialmente, $T$ lineal, polo que basta ver que é compacto. Vendo que $\dim T(L^2([a,b],\mathbb{F}))<\infty$, xa está, porque, así, como $T$ é continuo, tamén é limitado, e, así, a imaxe de cada conxunto limitado, é un subconxunto limitado dun espazo de dimensión finita e, polo tanto, precompacto. Este resultado verémolo máis tarde, probando que os operadores de rango finito son compactos.

$$Tf=\int_{a}^{b}\sum_{j,k=1}^{n}\alpha_{j,k}g_{j}\overline{g_{k}(s)}f(s)\,\text{d}s=\sum_{j,k=1}^{n}\alpha_{j,k}\left(\int_{a}^{b}\overline{g_{k}(s)}f(s)\,\text{d}s\right)g_{j}\in\langle g_{1},...,g_{n}\rangle$$ 
Así, $\dim T(L^2([a,b],\mathbb{F}))\leq n$ e, polo tanto, $T$ compacto.

## Apartado c) Calcula $\sigma_{p}(T), \sigma(T)$ e $R_{T}$.

Por ser $T$ de rango finito, $\sigma_{p}(T)$ é finito. Ademais, por ser $T$ compacto, $\sigma(T)=\sigma_{p}(T)\cup\{0\}$. Polo tanto, basta calcular os autovectores de $T$, que están no espazo $\langle g_{1},...,g_{n}\rangle$.

Sexa $f=\sum_{i=1}^{n}\beta_{i}g_{i}$. $$Tf=\sum_{j,k=1}^{n}\alpha_{j,k}\left(\int_{a}^{b}\overline{g_{k}(s)}\sum_{i=1}^{n}\beta_{i}g_{i}(s)\,\text{d}s\right)g_{j}=\sum_{j,k=1}^{n}\left(\alpha_{j,k}\sum_{i=1}^{n}\beta_{i}\delta_{k}^{i}\right)g_{j}=\sum_{j,k=1}^{n}\alpha_{j,k}\beta_{k}g_{j}$$   
Así, para que $Tf=\lambda f$, $\lambda \beta_{i}=\sum_{k=1}^{n}\alpha_{i,k}\beta_{k},\forall 1\leq i\leq n$, é dicir, o vector $\beta=(\beta_{1},...,\beta_{n})$ é un autovector de autovalor $\lambda$ da matriz $A=(\alpha_{i,j})_{i,j=1}^{n}$. 

Así, $\sigma_{p}(T)=\{\text{Autovalores de }A\}$ e $\sigma(T)=\{\text{Autovalores de }A\}\cup\{0\}$.

Nota: No caso de que $\mathbb{F}=\mathbb{R}$, teñen que ser os autovalores reais de $A$.

Para calcular $R_{T}(z)$, temos que calcular $(z\id-T)^{-1}$ para $z\in\rho(T)=\mathbb{F}\setminus\sigma(T)$.



## Apartado d) Calcula $\cosh T$.

Se consideramos $V=\langle g_{1},...,g_{n}\rangle \bigoplus \langle g_{1},...,g_{n}\rangle^{\perp}$, $T$ ten por matriz por bloques $$M=\begin{pmatrix}A&0\\0&0\end{pmatrix}$$ 
polo que $\cosh T=\begin{pmatrix}\cosh A&0\\0&1\end{pmatrix}$.

## Apartado e) Calcula $\ker T$.

$\ker T=\langle g_{1},...,g_{n}\rangle^{\perp}\bigoplus\langle \sum_{i=1}^{n} \beta_{i}g_{i} \rangle$ con $(\beta_{1},...,\beta_{n})=\beta\in\ker A$.

Non hai que nada que demostrar porque, claramente, o ortogonal está contido no $\ker$ e o outro está xerado por unha cantidade finita de vectores.

## Apartado f) Calcula $T(L^{2}([a,b],\mathbb{F}))$.

$T(L^{2}([a,b],\mathbb{F}))=\langle \sum_{i=1}^{n} \beta_{i}g_{i} \rangle$ con $(\beta_{1},...,\beta_{n})=\beta\in A(\mathbb{F}^{n})$.