# Die Restklassengruppe modulo $n$
- Gegeben: $n \in \mathbb N$ 
- $G = \mathbb Z, \space U = n\mathbb Z$   (Additiv)
- $a + n\mathbb Z = \{...,\space a-2n, \space a-n, \space a+0,\space a+n, \space a+2n,\space ...\}$ 
- Setze:
$$\begin{align}
\overline a := a +n\mathbb Z = \{a, a+n,...
\\
a-n,...\}
\\
=\{a+nz\mid z\in \mathbb Z \}
\end{align}$$
- Sei $m \in \mathbb Z \to$ Division mit Rest durch n: 
$$ m= qn + r $$ $$r\in \{0, 1, ..., n-1\} \space\space mit$$
$$m \in r + n \mathbb Z = \overline r$$
$$\mathbb Z \subseteq \bigcup_{\{0,...,n-1\}}r+n\mathbb Z $$ 
- Man nennt $\overline 0, \overline 1, ..., \overline{n-1}$ die Restklassen modulo n. Elemente in der gleichen Restklasse sind kongruent.
- Es gilt mit der Notation $a \equiv b \mod n : \Leftrightarrow$ $a, b$ haben bei Division durch $n$ mit Rest den gleichen Rest. 

$$

\begin{align}
Satz: \space a \equiv_n b & \Leftrightarrow n \mid a-b \\
&\Leftrightarrow a + n\mathbb Z = b  + n \mathbb Z\\
&\Leftrightarrow \overline a = \overline b
\end{align}
$$
$$
\begin{align}
Denn: a&\equiv_n b \Leftrightarrow\\
a &= qn + r^{\star^1}\\
b&=q'n+r^{\star^2}
\\
r^{\star^1} &= r^{\star^2} \Leftrightarrow a-b = (q-q')n\\
&\Leftrightarrow n \mid a-b \Leftrightarrow a = b+kn \\
& \Leftrightarrow...\Leftrightarrow a+n\mathbb Z = b+n\mathbb Z \\
& \Leftrightarrow \overline a = \overline b \space \square
\end{align}
$$

- $\mathbb Z \space \% \space n\mathbb Z = \mathbb Z \space \% \space n = \mathbb Z_n  =\{\overline 0, \overline 1, ... \overline{n-1}\}$ 
- Klar: $|\mathbb Z_n| = n$
- Addition: $\overline k, \overline l \in \mathbb Z_n$,  $\overline k + \overline l := \overline{k+l}$
- Damit: $(\mathbb Z_n, +)$ ist eine abelsche Gruppe

# Prime Restklassengruppen
- Über ein beliebiges $n \in \mathbb N$ wird die Restklassengruppe modulo $n$ definiert, wobei jedes Element invertierbar ist
$$\mathbb Z ^\times _n = \{a \in \mathbb Z_n \mid ggT(a, n) = 1\}$$

- Die eulersche $\varphi-$Funktion wird mit einem beliebigen $n \in \mathbb N$ definiert durch $\varphi(n) = |\mathbb Z^\times|$
- Ist $p \in \mathbb N$ prim, so ist $\varphi(p) = p - 1$ 