### Start: $\mathbb R^2 = \{(a, b) | a, b \in \mathbb R \}$ 
- Die erste Achse ist die reelle Achse 
	- Zahlen Die auf der ersten Achse liegen haben einen Imaginärteil von $0$. 
- Die zweite Achse ist die Imaginäre Achse. 

### Einführung der Addition: 
$$(a, b) + (c, d):=(a + c, b + d)$$
- Neutrales Element: $(0, 0)$ 
- additives Inverses von $(a, b): (-a, -b)$

#### Bsp:
$$(1, 1) + (4, 2) = (1 + 4, 1 + 2) = (5, 3)$$

### Einführung der Multiplikation
$$(a, b) \cdot (c, d) = (ac-bd, ad+bc)$$
- Neutrales Element: $(1, 0)$
	- $(1, 0)(c, d)= (c - 0, d + 0) = (c, d)$
- Inverses Element: zu $(a, b) \in \mathbb R ^2\setminus \{(0, 0)\}$ : $(a, b)^-1=(\frac{a}{a^2+b^2}, \frac{-b}{a^2 + b^2})$ 
- $(2, 1)(\frac 25, \frac{-1}5) = (1, 0)$ 
- $(2, 1)^{-1} = (\frac{2}{5}, \frac{-1}{5})$ 
- Man kann ein Element duch einen einfachen [[Trick zum Invertieren|Trick ]] invertieren

#### Bsp:
$$(1, 1)\cdot (4, 2)= (1\cdot 4 - 1 \cdot 2 + 1\cdot 4)$$

Somit Erhalten wir $\textcolor{#A0AAFB}{(\mathbb R^2, +, \cdot)}$. Es handelt sich dabei um die algebraische Struktur eines [[5 Algebraische Strukturen|Körpers]] 

#### Umwandeln von $\mathbb C$ nach $\mathbb R$ 

- $(a, 0)$ kann als $a$ geschrieben werden, da die $0$ für Addition, Multiplikation und Negation keine relevanten Informationen enthält. 
- **Setze:** $(0, 1)=:$ die Imaginäre Einheit
	- Damit: $(a, b) =(a, 0) \textcolor{#A0AAFB}{(0, b)^*} = (a, 0)+\textcolor{#A0AAFB}{(b, 0)(0, 1)^*}= a + bi$ 
	 -   $(b\cdot0-0\cdot1, b\cdot 1 + 0 \cdot 0) = (0, b)$ 
	 -  $\textcolor{#A0AAFB}{\mathbb C = \{a + ib | a, b \in \mathbb R \}}$ -> Komplexe Zahlen $(\mathbb C, +, \cdot)$ : Körper der komplexen Zahlen
	-  $\textcolor{#A0AAFB}{i^2}= i\cdot i=(0 + i)\cdot (0 + i) = (0\cdot 0-1, 0+0) = (-1, 0)= \textcolor{#A0AAFB}{-1}$
- $(a + ib)(a - ib) = a^2 + b^2 \in \mathbb R$ -> Imaginärteil = 0
- zB: $(3 + 4i)(3-4i) = 25$ 

