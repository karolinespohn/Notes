Modulo Tricks anhand folgendem Beispiel:
###### Fermat 
 - falls $p \not \mid a$ 
$$
\forall a \in \mathbb Z: a^{p-1} = 1 \mod p
$$
- falls $p \mid a$:
$$
\forall a \in \mathbb Z: a ^p = a \mod p
$$
- Beispiel 1:
$$\begin{gather}
137^{58}\equiv_{47} 137^{12}\cdot137^{46} \\
47 \in \mathbb P \\
\text{Damit: } 137^{46} \equiv_{47} 1\\
137^{58} \equiv_{47} 137^{12}
\end{gather}$$
- Teils kann man die Potenz auch auseinanderziehen und einen Term dadurch vereinfachen
- Beispiel 2: 
$$2 ^{340}\equiv_{11} (2^{10})^{34}\equiv_{11}1^{34}=1$$
###### Basis vereinfachen
$$\begin{gather} 
a^{x} \equiv_{b} (a  \mod b )^{x}\\
\end{gather}$$
- Beispiel: 
$$
137^{12}\equiv_{47} 43^{12} 
$$
###### Aequivalenzklassen
$$
a^x\equiv_b(a + b)^x\equiv(a-b)^x
$$
- Beispiel: 
$$43^{12}\equiv(-4)^{12}$$