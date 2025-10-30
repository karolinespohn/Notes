# Bestimmte Integrale
- Bei Integralen wie demfolgenden, macht es Sinn, den Bruch aufzuspalten
$$\int_2^4\frac{x^2+x+1}{x} = \int_2^4x + 1 + \frac 1x$$
# Uneigentliche Integrale
- Um festzustellen, ob ein uneigentliches Integral existiert, muss man mit dem Limes arbeiten
- Auch wenn eine Fkt, beispielsweise $\ln$ in $0$ nicht definiert ist, kann das Integral $\int_0^a \ln(x) dx$ existieren
# Partialbruchzerlegung
- Gegeben sei ein Bruch der Form:
$$n:=\frac{2x^2+x+9}{(x+1)(x^2+4)}=\frac{a}{x+1}+ \frac{bx+c}{x^2+4}:=m$$
- Multiplikationm it dem Nenner von $n$
$$n:=2x^2+x+9=a(x^2+4)+(bx+c)(x+1)$$
- Ausklammern von $x^2$ und $x$
$$2x^2+x+9=ax^2+4a+bx^2+bx +cx +c= x^2(a + b)+x(b + c)+ 4a + c$$
- Koeffizientenvergleich:
$$a + b = 2$$
$$b + c =1$$
$$4a + c = 8$$
- Loesen des LGS:
$$
\left (
\begin{array}{ccc|c}
1 & 1 & 0 & 2 \\
0 & 1 & 1 & 1\\
4 & 0 & 1 & 1
\end{array}
\right)
$$
