## Gruppen
$$G= 
\begin{cases}
G\times G \to G
\\
(a,b) \mapsto a\cdot b
\end{cases}
$$
- Die Menge $G$ mit innerer Vernkuepfung heisst Gruppe, falls
$$\begin{gather}
(1). \quad \forall \space a, b, c \in G: \space a\cdot(b \cdot c ) = (a\cdot b)\cdot c \\
(2). \quad \exists \space e \in \ G: ea = a = ae \\
(3). \forall \space a \in G \space \exists b \in G : ab = e =ba \quad b = a^{-1} 
\end{gather}$$
- Rezept Gruppenbeweis fuer $G$:
1. $G$ hat innere Verknüpfungen
3. $G$ ist assoziativ
4. $G$ hat ein neutrales Element
5. Jedes $a \in G$ besitzt ein Inverses

- $G$ heißt abelsch, falls $ab=ba \space \forall a, b \in G$ 
#### Untergruppen
- $(G, \cdot)$ sei eine Gruppe mit neutralem Element $e$
Eine Teilmenge $U\subseteq G$ heißt Untergruppe von $G$ falls:
- $e \in U$
- $u, v \in U \to u\cdot v \in U$
- $u\in U \to u^{-1} \in U$ 

- Rezept Untergruppenbeweis fuer $U$:
1. $U$ ist Teilmenge von $G$
2. $U$ enthält ein neutrales Element
3. $U$ ist abgeschlossen
4. Jedes $a \in U$ beseitzt ein Inverses
#### Die Einheitsgruppe eines Rings mit Einselement
Gegeben: Ring$(R,+,\cdot)$ mit $1$. 
$$
\begin{align}
&1\cdot 1 = 1 \\
&1 \cdot a = a \\
& R^{\times} = \{a\in R \mid \text{a ist invertierbar}\} &=\\
&\downarrow  \space = \{ a\in R \mid \exists b \in R: ab = 1 = ba \} &= \\
& (R^{\times}, \cdot) \text{ Gruppe}
\end{align}
$$
- Man nennt $(R^{\times}, \cdot)$ die Einheitsgruppe von $R$

- $\mathbb Q^\times = \mathbb Q \setminus \{0\}$ 
- $\mathbb R^\times = \mathbb R \setminus \{0\}$ 
- $\mathbb C^\times = \mathbb C \setminus \{0\}$ 

###### Die von Elementen erzeugten Untergruppen
- $(G, \cdot)$ sei eine Gruppe und $a \in G$
-  $\langle a\rangle = \{ a^k \mid k\in \mathbb Z\}\subseteq G$  
$$
[a^0:=e^{\star^1}, \space a^k =a\cdot...\cdot a, k \in \mathbb N, \space a^{-k}=(a^{-1})^k]
$$
$\star^1: e = Einselement$ 

- Beweis $\langle a\rangle \le G$ (ist Untergruppe von G)
1. $\langle a \rangle \subseteq G$ 
2. $e \in \langle a \rangle: e = a^0$
3. $a^k, a^l \to a^k \cdot a ^l = a ^{k+l} \space \in \langle a \rangle$ 
4. $a^k\to a^ka^{-k}=a^0=e$ 

#### Die Ordnung eines Elementes $a \in G$
- $(G, \cdot)$ sei eine Gruppe $\to \space a \in G$
- $ord(a)= n =$ kleinste Zahl mit $a^n=e$ 
- Es gelten [[1. Sätze| der Satz über die Ordnung von Gruppen Elementen, der Satz von Lagrange und der Satz von Euler]] 
## Ringe
- Sei $\mathbb G$ eine Gruppe mit den inneren Verknüpfungen $+$ und $\cdot$ 
- $(\mathbb G, +, \cdot)$ ist ein Ring, wenn:
	- $(\mathbb G, +)$ eine abelsche Gruppe bildet
	- Die Multiplikation $\cdot$ assoziativ ist
	- Die Distributivgesetze gelten
$$
\forall \space a, b, c\in \mathbb G: a\cdot (b+c) = a\cdot b + a\cdot c
$$
#### Kommutativer Ring
- Ein Ring $(\mathbb G, +, \cdot)$ ist kommutativ, falls
$$
\exists e \in \mathbb G: \forall a \in \mathbb G:a\cdot b = b \cdot a
$$
#### Ring mit Einselement
- Ein Ring $(\mathbb G,+, \cdot )$ besitzt ein Einselement, falls
$$
\exists e \in \mathbb G: \forall a \in \mathbb G: a \cdot e = a
$$
## Körper
- Sei $\mathbb G$ eine Gruppe mit den inneren Verknüpfungen $+$ und $\cdot$ 
- Man nennt $(\mathbb G, +, \cdot)$ einen Körper, wenn
	- $(\mathbb G, +)$ eine abelsche Gruppe bildet
	- $(G\setminus 0, \cdot)$ eine abelsche Gruppe bildet
	- Die Distributivgesetze gelten
$$
\forall \space a, b, c\in \mathbb G: a\cdot (b+c) = a\cdot b + a\cdot c
$$
