# Sexa $a\in\mathbb{R}$. Dada $f:\mathbb{R}\to\mathbb{F}$ definimos $T_{a}f(x)=f(x+a),x\in\mathbb{R}$. Sexan $f,g\in\mathcal{C}_{c}^{\infty}(\mathbb{R},\mathbb{F})$. Demostra que $T_{a}(f\ast g)=(T_{a}f)\ast g=f\ast (T_{a}g)$.

Dado que $f\ast g=g\ast f$, basta con probar a primeira igualdade.

$$T_{a}(f\ast g)(x)=(f\ast g)(x+a)=\int_{\mathbb{R}}f(y)g(x+a-y)\,\text{d}y\overset{y=t+a\Rightarrow \text{d}y=\text{d}t }{=}\int_{\mathbb{R}}f(t+a)g(x+a-t-a)\,\text{d}t=\int_{\mathbb{R}}T_{a}f(t)g(x-t)\,\text{d}t=\left((T_{a}f)\ast g\right)(x)$$
Polo tanto, $(T_{a}f)\ast g=T_{a}(f\ast g)=T_{a}(g\ast f)=(T_{a}g)\ast f=f\ast (T_{a}g)$.