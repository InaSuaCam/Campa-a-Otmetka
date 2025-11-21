# Sexa $f,g\in\mathcal{C}_{c}^{\infty}(\mathbb{R},\mathbb{R})$, $F$ unha primitiva de $f$.

## Apartado a) Define a convolución $f\ast g$ de $f$ e $g$ e demostra que está ben definida.

Por definición, $(f\ast g)(x):=\int_{\mathbb{R}}f(y)g(x-y)\,\text{d}y$. Vexamos que está ben definida.

Como $f$ e $g$ son de clase infinito, tamén o é $h(x,y)=f(y)g(x-y)$. Ademais, como $f$ e $g$ son de soporte compacto, $h$ tamén. Así, $h_{x}=h(x,\cdot)$ é de clase infinito e soporte compacto, $\forall x\in\mathbb{R}$. Polo tanto, $\exists \int_{\mathbb{R}}f(y)g(x-y)\,\text{d}y=(f\ast g)(x),\forall x\in\mathbb{R}$.

## Apartado b) Demostra que $F\ast g$ está ben definida.

Como $f$ é clase infinito, $F$ tamén. Vexamos que $F$ está limitada. $$\lvert F(x)\rvert=\left\lvert\int_{-\infty}^{x}f(t)\,\text{d}t\right\rvert\leq\int_{-\infty}^{x}\lvert f(t)\rvert\,\text{d}t\leq\int_{-\infty}^{\infty}\lvert f(t)\rvert\,\text{d}t=\lvert\lvert f\rvert\rvert_{1}$$ Así, $\lvert\lvert F\rvert\rvert_{\infty}\leq\lvert\lvert f\rvert\rvert_{1}$, probando que $F$ é limitada.

Como $F$ e $g$ son de clase infinito, tamén o é $H(x,y)=F(y)g(x-y)$. Ademais, como $g$ é de soporte compacto, $H$ tamén. Así, $H_{x}=H(x,\cdot)$ é de clase infinito e soporte compacto, $\forall x\in\mathbb{R}$. Polo tanto, $\exists \int_{\mathbb{R}}F(y)g(x-y)\,\text{d}y=(F\ast g)(x),\forall x\in\mathbb{R}$.

## Apartado c) Dados $a,b\in\mathbb{R}$, $a<b$, demostra que $$\int_{a}^{b}(f\ast g)(x)\,\text{d}x=(F\ast g)(b)-(F\ast g)(a)$$
Basta ver que $(F\ast g)'=(f\ast g)$.

$$(F\ast g)'(x):=\frac{\text{d}}{\text{d}x}\int_{\mathbb{R}}g(y)F(x-y)\,\text{d}y=\int_{\mathbb{R}}\frac{\partial}{\partial x}g(y)F(x-y)\,\text{d}y=\int_{\mathbb{R}}g(y)f(x-y)\,\text{d}y=(f\ast g)(x)$$