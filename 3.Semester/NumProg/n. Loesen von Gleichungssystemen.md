# Basics
- Das Loesen von [[n. Loesen von Gleichungssystemen|LGS]] ist eine Vorraussetzung fuer Probleme wie Interpolation, Grenzwertprobleme und Pratielle Ableitungen
## Volle Matritzen und Sparse Matritzen
- Volle Matritzen sind Matritzen, in denen die Nichtnulleintraege dieselbe Groessenordnung wie die Anzahl aller Eintraege besitzt
- In Sparse Matritzen uebertrifft die Anzahl an Nulleintraegen die der Nichtnulleintraege
- Oft verfuegen Sparse Matritzen ueber gewisse Muster, die die Loesung eines LGS vereinfachen
![[Sparsity Patterns.png|700]]
## Direkte und Indirekte Loesungsansaetze
- Bei direkten Loesungen wird die genaue Loesung (mit Rundungsfehlern) eines LGS errechnet 
- Bei indirekten Loesungen naehert man sich durch wiederholte Approximationen dem Ergebnis an, ohne es zu erreichen
## Vektornormen
- Eine [[Matrixnormen| Vektornorm]] ist eine Funktion $||\cdot||$ mit den folgenden Eigenschaften:
- Positivitaet:
$$||x|| > 0 \forall x \neq 0$$
- Homogenitaet:
$$||\alpha x|| = ||||$$