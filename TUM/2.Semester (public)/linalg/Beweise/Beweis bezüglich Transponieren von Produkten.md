- $A, B: A\in K^{m\times n}, \lambda \in K: \space (AB)^T = B^TA^T$ 
- Matrizen sind genau dann gleich, wenn die Dimensionen gleich sind und beide Matrizen an jeder Stelle die gleichen Einträge haben
###### $(AB)^T \text{ ist so groß wie } B^TA^T:$ 
- Sei $A$ eine $m\times n$ Matrix und $B$ eine $n\times p$ Matrix. 
- Multipliziert man $A$ und $B$ erhält man eine $m\times p$ Matrix. Transponiert man $AB$ so erhält man eine $p\times m$ Matrix
- Transponiert man  $A$, so erhält man eine $n\times m$ Matrix. Transponiert man $B$ so erhält man eine $p\times n$ Matrix. Multipliziert man eine $p\times n$ Matrix mit einer $n\times m$ Matrix, so erhält man eine $p\times m$ Matrix
- $\square$ $(AB)^T \text{ hat die gleichen Dimensionen wie } B^TA^T$ 
###### An jeder stelle von $(AB)^T$ steht der gleiche Eintrag wie in $B^TA^T$ 
- $AB^T \to^? (i,j):$
$$
\begin{align}
A=\begin{pmatrix}
z_1
\\
\vdots
\\
z_m
\end{pmatrix}
\\
\\
B=
\begin{pmatrix}
s_1 & ... &  s_p
\end{pmatrix}
\\
\\
(ji): z_js_i
\end{align}
$$
- $(AB)^T \to (i,j): z_js_i\space^{\star^1}$  
 
- $B^TA^T \to^? (i,j):$
$$
\begin{align}
B^T=
\begin{pmatrix}
s_1^T
\\
\vdots
\\
s_p^T
\end{pmatrix}
\\
\\
A^T=
\begin{pmatrix}
z_1 ^T & ... & z_m^T
\end{pmatrix}
\\
\\
(ij):s_i\space^T\cdot z_j^{T}

\end{align}
$$

- $B^TA^T \to(i,j):s_i\space^Tz_j\space^T\space ^{\star^2}$ 

- ist  $z_js_i ^{\star^1}= s_i\space^Tz_j\space ^T \space ^{\star^2}$?
$$
\star^1:
\begin{pmatrix}
a_1 & ... & a_n
\end{pmatrix}

\begin{pmatrix}
b_1
\\
\vdots
\\
b_n
\end{pmatrix}
$$
$$
\star^2:
\begin{pmatrix}
b_1 & ... & b_n
\end{pmatrix}
\begin{pmatrix}
a_1
\\
\vdots
\\
a_n
\end{pmatrix}
$$


