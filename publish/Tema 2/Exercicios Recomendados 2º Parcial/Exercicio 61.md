# Sexa $V$ un espazo vectorial. Demostra que:
## Apartado a) Se $P:V\to V$ é unha proxección, tense que $P|_{P(V)}=\text{Id}$, $P|_{(\text{Id}-P)(V)}=0$, $V=P(V)\bigoplus(\text{Id}-P)(V)$, $P(V)=\ker{(\text{Id}-P)}$ e $(\text{Id}-P)(V)=\ker{P}$.

$P$ é unha proxección de $P^2=P$. Polo tanto, se $u\in P(V),\exists v\in V/ u=Pv$ e $Pu=P^2v=Pv=u$, polo que $P|_{P(V)}=\text{Id}$. Analogamente,  se $u\in (\text{Id}-P)(V),\exists v\in V/ u=v-Pv$ e $Pu=Pv-P^2v=Pv-Pv=0$, polo que $P|_{(\text{Id}-P)(V)}=0$.

Claramente, $P(V)+(\text{Id}-P)(V)\subset V$. Sexa $v\in V$. Definimos $u=Pv$ e $w=v-Pv$. Claramente, $v=u+w$, $u\in P(V)$ e $w\in (\id-P)(V)$, polo que $V\subset P(V)+(\id-P)(V)$.
Vexamos que $P(V)\cap(\id-P)(V)=\{0\}$. Se $v\in P(V)\cap(\id-P)(V)$, $Pv=v$ porque $v\in P(V)$ e $Pv=0$ porque $v\in(\id-P)(V)$. Así, $v=0$ e $P(V)\cap(\id-P)(V)=\{0\}$, concluíndo que $V=P(V)\bigoplus(\text{Id}-P)(V)$.

Se $v\in \ker(\id-P)$, $(\id-P)v=0\iff v-Pv=0\iff v=Pv$, polo que $v\in P(V)$. Se $v\in P(V),\exists u\in V/ v=Pu$ e $(\id-P)v=v-Pv=Pu-P^2u=Pu-Pu=0$ e $v\in\ker(\id-P)$. Polo tanto, $P(V)=\ker{(\text{Id}-P)}$. Analogamente, Se $v\in \ker P$, $Pv=0\iff Pv=0\iff v=v-Pv$, polo que $v\in (\id-P)(V)$. Se $v\in (\id-P)(V),\exists u\in V/ v=u-Pu$ e $Pv=Pu-P^2u=Pu-Pu=0$ e $v\in\ker P$. Polo tanto, $(\text{Id}-P)(V)=\ker{P}$.

## Apartado b) Se $U$ é un subespazo de $V$ e $W\subset V$ é un subespazo tal que $U\bigoplus W=V$, entón existe unha única proxección $P:V\to V$ tal que $P(V)=U$ e $\ker P=W$.

### Existencia:

Sexa $v\in V$. Entón, existen uns únicos $u\in U$ e $w\in W$ tales que $v=u+w$. Así, definimos $Pv=u$. $P$ trivialmente proxección.

### Unicidade:

Sexan $P$ e $Q$ dúas proxeccións tales que $P(V)=Q(V)=U$ e $\ker P=\ker Q=W$.
Se $u\in U$, $(P-Q)u=Pu-Qu=u-u=0$. Se $w\in W$, $(P-Q)w=Pw-Qw=0-0=0$. Así, $(P-Q)v=0,\forall v\in V$ e, polo tanto, $P-Q=0\iff P=Q$.