Ist $z \in \mathbb C$ Nullstelle eines reellen Polynoms $p=a_nx^n+...+a_1x+a_0$ mit $a_0,...,a_n\in \mathbb R$, so auch $\overline z \in C$.


 - $f(z)=0$
 - $f(x) \sum^n_{k=0} a_k(\overline z)^{k}$
 - zu Zeigen: $f(\overline z) = 0$

$$
\begin{aligned}
f(\overline z) = \sum^n_{k=0}a_k(\overline z)^{k}=
\\
= \sum^n_{k=0}a_k(\overline z^{k})=\star^1
\\
=\sum^n_{k=0}\overline{a_k(z^{k})} = \star^2
\\ 
=\overline{\sum^n_{k = 0}a_k\cdot z^k} = \star^3
\\
=\overline {f(z)} = \overline 0 = 0
\end{aligned}
$$ 
$\star^1$ $\overline z \cdot \overline z =\overline{z\cdot z}$
$\star^2$ erlaubt, weil $a_k$ reell ist und somit $a_k=\overline{a_k}$ 
$\star^3 \overline z + \overline z =\overline{z+z}$

bzw.:
- $p=a_kx^k + ... + a_1x+a_0$ 
$$
\begin{align}
p=a_k\overline{x^k} + ... + a_1\overline x+a_0=
\\
= \overline{a_kx^k} + ... + \overline{a_1x}+ \overline {a_0} =
\\
=\overline{a_kx^k+...+a_1x+a_0}
\\
\\
p(z) = a_kz^k+...+a_1z+a_0 =0
\\
\overline{p(z)} = \overline{a_kz^k+...+a_1z+a_0}=\overline 0
\end{align}
$$