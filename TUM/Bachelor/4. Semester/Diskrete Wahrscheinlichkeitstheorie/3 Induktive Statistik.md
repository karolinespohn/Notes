###### Latex Math Operators$\DeclareMathOperator{Bin}{Bin} \DeclareMathOperator{Var}{Var} \DeclareMathOperator{E}{\mathbb E} \DeclareMathOperator{Po}{Po} \DeclareMathOperator{sumx[lower][upper]}{\sum_{lower}^{upper}} \DeclareMathOperator{\dx}{\; \mathrm d x}\DeclareMathOperator{\dt}{\; \mathrm d t} \DeclareMathOperator{\Nv}{\mathcal N} \DeclareMathOperator{MSE}{MSE}$
# Ziel
- Das Ziel der Induktiven Statistik ist, aus gemessenen Zufallsgroessen Gesetzmaessigkeiten abzuleiten
# Schaetzvariablen
- Es sei $X$ eine Zufallsvariable mit der Dichte $f(x;\theta)$ 
- Eine Schaetzvariable $\overline X$ fuer $\theta$ wird zusammengesetzt aus mehreren Stichproben fuer $X$
- $\overline X$ ist **erwartungsgetreu**, wenn gilt: 
$$\E[\overline X] = \theta$$
- Die **Bias** von $\overline X$ ist definiert durch $\E[\overline X - \theta]$ 
## Mean Squared Error
- Das MSE bietet ein Mass fuer die Guete einer Schaetzvariable
$$\MSE(\overline{X}) = \mathbb{E}[(\overline{X} - \theta)^2]$$
- Ist $\overline X$ erwartungsgetreu, gilt $\MSE[\overline X] = \Var[\overline X]$ und damit bei $n$ Stichproben: 
$$\MSE(\overline{X}) = \Var[\overline{X}] = \frac{1}{n}\Var[X]$$
## Stichprobenmittel und -varianz
- Das Stichprobenmittel der Stichproben $X_1,...,X_n$ ist definiert wiefolgt:
$$\overline X= \frac 1n \sum_{i = 1}^nX_i$$
- Die Stichprobenvarianz ist definiert wiefolgt:
$$S^2 := \frac1{n-1}\sum_{i = 1}^n(X_i- \overline X)^2$$
- $\overline X$ und $S^2$ sind erwartungstreue Schaetzer fuer Erwartungswert und Varianz

## Maximum-Likelihood-Prinzip
- Das Maximum-Likelihood-Prinzip ist ein Verfahren fuer die Konstruktion von Schaetzvariablen
- Wir definieren $\vec X = (X_1,...,X_n)$ als unabhaengige Kopien von $X$ und $\vec x = (x_1,...,x_n)$ eine zugehoerige Stichprobe
- Es sei weiters $f(x_i; \theta)$ die Dichtefunktion von $X_i$ in abhaengigkeit von $\theta$ 
- Eine **Likelihood-Funktion** kann definiert werden wiefolgt:
$$L(\vec{x}, \theta)= \prod_{i = 1}^n f(x_i; \theta)= \prod_{i = 1}^n\Pr[X_i = x_i]=  Pr_{\theta}[X_1 = x_1, ..., X_n = x_n]$$
- $L(\vec x, \theta)$ beschreibt die Wahrscheinlichkeit, fuer den Parameter $\theta$ die Stichprobe $x_i$ zu erhalten
- Der **Maximum-Likelihood-Schaetzwert** ist der Schaetzwert $\hat \theta$ fuer $\theta$ fuer den gilt:
$$L(\vec{x}, \theta) \leq L(\vec{x}, \hat{\theta}), \; \forall\, \theta$$