# Mathe 5


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Mathe 5](#mathe-5)
  - [Gebrochen rationale Funktion](#gebrochen-rationale-funktion)
    - [Definitions Bereich](#definitions-bereich)
    - [Symmetrie](#symmetrie)
    - [Achsen schnittpunkte](#achsen-schnittpunkte)
      - [Y achse](#y-achse)
      - [X Achse (Nullstellen)](#x-achse-nullstellen)
    - [Extrempunkte](#extrempunkte)
    - [Asymptoten](#asymptoten)
    - [Prüfen auf behebbare defintions Lücken](#prüfen-auf-behebbare-defintions-lücken)
    - [Tangenten](#tangenten)
    - [Steigungsverhalten montonioe verhalten](#steigungsverhalten-montonioe-verhalten)
    - [Verhalten im unendlichen](#verhalten-im-unendlichen)
  - [I'Hospital](#ihospital)
  - [KuvenDiskussion  $e$ funktion](#kuvendiskussion--e-funktion)
    - [Was ist $e$ Funktion](#was-ist-e-funktion)
    - [Symetrie](#symetrie)
    - [Nullstellen](#nullstellen)
    - [Vorzeichen Verteilung](#vorzeichen-verteilung)
    - [Y-achsen Abschnitt](#y-achsen-abschnitt)
    - [Asymtoten](#asymtoten)
    - [Abletungen](#abletungen)
    - [Monitonoieverhalten](#monitonoieverhalten)
    - [Extrempunkte](#extrempunkte-1)
    - [Krümmungsverhalten](#krümmungsverhalten)
    - [Wendepunkte](#wendepunkte)

<!-- /code_chunk_output -->

## Gebrochen rationale Funktion

$$
f(x)=\frac{Z(x) \text{ ZählerFunktion}}{N(x) \text{ NennerFunktion}}
$$

$$
f(x)=\frac{x^2+1}{x};\qquad \mathbb{g}=\mathbb{R}
$$

### Definitions Bereich

wenn die Nenner Funktion null ist

$$
N(x)=0 \implies x=0 \quad \mathbb{D}=\mathbb{R} \backslash \{ 0\}
$$

### Symmetrie

$$
f(x)=f(-x) A.S\\
f(x)=-f(-x) P.S
$$

$$
f(-x)=\frac{(-x)^2+1}{-x}=\frac{x^2+1}{-x}=-\frac{x^2+1}{x}\implies \text{ nicht A.S}
$$

$$
-f(-x) = --\frac{x^2+1}{x}=+\frac{x^2+1}{x}=f(x)\implies f(x) \text{ ist P.S zum Ursprung}
$$

### Achsen schnittpunkte

#### Y achse

kein $Sy$, da F(0) nicht definiert

$$
f(x)=\frac{Z(x)}{N(x)}=0 \quad |*N(x) \\
Z(x)=0
$$

#### X Achse (Nullstellen)

NST:

$$
\begin{align*}
f(x)=0\implies Z(x)&=0 \\
x^2+1&=0  &|&-1\\
x^2&=-1 &|&\sqrt{} \\
 |x|&=\sqrt{-1} &\implies& \text{ Keine NST}
\end{align*}
$$

### Extrempunkte

Erste Ableitung

$$
\begin{align*}
  f(x)&=\frac{x^2+1}{x} \qquad \text{ableitungs regel nutzen} \qquad \frac{N*Az-Z*AN}{N^2}\\
  f'(x)&=\frac{x*2x-(x^2+1)*1}{x^2}\\
  f'(x)&=\frac{2x^2-x^2-1}{x^2}\\
  f'(x)&=\frac{x^2-1}{x^2} \quad \text{bruch auf spalten}\\
  f'(x)&=\frac{x^2}{x^2}-\frac{1}{x^2} \\
  f'(x)&=1-\frac{1}{x^2}
\end{align*}
$$

$$
f'(x)=1-\frac{1}{x^2} = 1-x^{-2}\\
f''(x)=2x^{-3}=\frac{2}{x^3}
$$

$$
\begin{align*}
f'(x_0)=0 &:& 1-\frac{1}{x^2}&=0 &|& -1 \\
&& -\frac{1}{x^2}&=-1 &|&*(-x^2) \\
&& 1&=x^2 &|& \sqrt{}\\
&& |x|&=1 && 
\end{align*}
$$
$$
\begin{align*}
\implies x_1 &=1\\
x_2&=-1
\end{align*}
$$
  
$$
\begin{align*}
f''(x_1)&=f''(1) &=2&>0&\implies& TIP (1|2)\\
f''(x_2)&=f''(-1)&=-2&<0&\implies& HOP (-1|-2) \\
\qquad\\
f(x_1)&=f(1)&=2\\
f(x_2)&=f(-1)&=-2
\end{align*}
$$

### Asymptoten

Höchste expnenenten im nenner und zähler

$$
\frac{x^3-20x^2+4}{30x^2+60x}
$$

Zähler $\implies 3$

Nenner $\implies 2$

|         |                                           |                                |                                                                                                                      |
|---------|-------------------------------------------|--------------------------------|----------------------------------------------------------------------------------------------------------------------|
| $m<n$   | Zählergrad < Nennergrad                   | Wagerechte Asymptote           | $A:y=0$                                                                                                              |
| $m=n$   | Zählergrad = Nennergrad                   | Wagerechte Asymptote           | $A:y=\frac{a_m}{b_n}$                                                                                                |
| $m=n+1$ | Zählergrad ist um 1 größer als Nennergrad | Schiefe oder schräge Asymptote | $x\rightarrow+\infty \implies f(x) \rightarrow \pm \infty\\x\rightarrow-\infty \implies f(x) \rightarrow \mp \infty$ |
| $m>n$   | Zählergrad > Nennergrad                   | Schiefe oder schräge Asymptote | $x\rightarrow+\infty \implies f(x) \rightarrow \pm \infty\\x\rightarrow-\infty \implies f(x) \rightarrow \pm \infty$ |

$3=2+1 \implies$ Schräge Asy. $\implies$  Polynomdivision

$$
\begin{aligned}
  &f(x)=& &(x^3  &&-20x^2  &&+0x+4)&:&(30x^2+60x)=\frac{1}{30}x-\frac{22}{30}+\frac{44x+4}{30x2+60x}\\
  &     &-&(x^3  &&+2x^2)  &&     &&\\
  &     & &0     &&-22x^2   &&+0x    &&\\
  &     & &      &&-(-22x^2&&-44x)&&\\
  &     & &      &&0       &&+44x+4     &&\\
\end{aligned}
$$

$$
A_1:y=\frac{1}{30}x+\frac{22}{30}
$$

### Prüfen auf behebbare defintions Lücken

$$
\begin{align*}
Z(x_1)&=Z(0) &&=x^3-20*0^2+4&=&&4 \neq0\\
Z(x_2)&=Z(-2)&&=(-2)^2-20*(-2)^2+4&=&&-8-80+4\neq0
\end{align*}\bigg\}\implies\text{Polstellen}
$$

$\implies$ Senkrechte Asymptoten.:
$A2: x_{p1}=-2\\ A3: x_{p2}=0$

### Tangenten

Tangente die die funktion in eine bestimmten x punkt berührt

m (steigung) errechnen indem man x in die erste abletung einsetzt

$$
m= f'(-2)=\frac{(-2)^2-(-2)-1}{(-2-0,5)^2}=\frac{4}{5}
$$

y brecrechnen indem man x in funktion einsetzt

$$
y=f(-2)=\frac{(-2)^2-4(-2)+3}{(-2)-0,5}=-6
$$

t brechnen

$$
-6=\frac{4}{5}(-2)+t\\
t=-\frac{22}{5}
$$

funktion aufstellen

$$
f(x)=\frac{4}{5}x-\frac{22}{5}
$$

### Steigungsverhalten montonioe verhalten

Die intervalle werden durch z.b. definitions lücken oder nullstellen

Deflücke = ${1}$
Nullstellen = ${0}$

$$
f(x)=\frac{2x^2}{(x-1)^2}\\
f'(x)=\frac{-4x^2+4x}{(x-1)^2}
$$

<svg xmlns="http://www.w3.org/2000/svg">
  <rect x="21" y="66" width="300" height="4" fill="rgb(0, 0, 0)" />
  <rect fill="rgb(0, 0, 0)" x="65" y="18" width="4" height="101" />
  <rect x="72" y="18" width="4" height="97" fill="rgb(0, 0, 0)" />
  <rect x="110" y="19" width="3" height="101" fill="rgb(0, 0, 0)" />
  <rect x="156" y="18" width="3" height="101" fill="rgb(0, 0, 0)" />
  <rect fill="rgb(0, 0, 0)" x="229" y="18" width="3" height="101" />
  <rect fill="rgb(0, 0, 0)" x="282" y="20" width="3" height="101" />
  <text textLength="21" font-size="38" x="35" y="49.9" fill="rgb(0, 0, 0)"> x</text>
  <text textLength="33.9" font-size="25" x="25.6" y="96.8" fill="rgb(0, 0, 0)"> f'(x)</text>
  <text textLength="38.9" font-size="41" x="80.6" y="103.2" fill="rgb(0, 0, 0)"> -</text>
  <text textLength="20" font-size="25" x="80.6" y="50" fill="rgb(0, 0, 0)"> -1</text>
  <text fill="rgb(0, 0, 0)" font-size="41" x="183.6" y="105.2" textLength="38.9">+</text>
  <text fill="rgb(0, 0, 0)" font-size="25" x="183.6" y="50" textLength="38.9">0,5</text>
  <text fill="rgb(0, 0, 0)" font-size="41" x="288.6" y="97.2" textLength="38.9">-</text>
  <text fill="rgb(0, 0, 0)" font-size="25" x="288.6" y="50" textLength="38.9">2</text>
  <text fill="rgb(0, 0, 0)" font-size="25" x="237.9" y="55.8" textLength="43.2">1</text>
  <text textLength="45" font-size="25" x="232" y="98.8" fill="rgb(0, 0, 0)">NaN</text>
  <text fill="rgb(0, 0, 0)" font-size="25" x="111.9" y="52.8" textLength="43.2">0</text>
  <text fill="rgb(0, 0, 0)" font-size="25" x="123.9" y="101.8" textLength="23.2">0</text>
</svg>

interwalle

$$
\begin{align*}
I_1 &]& -\infty&;0 &[ & FSM\\
I_2 &]& 0&;1 &[ &SSM\\
I_2 &]& 1&;\infty &[ &FSM\\
\end{align*}
$$


### Verhalten im unendlichen

in $\infty$ und $-\infty$ I'Hospital Nutzen

$$
f(x)=\frac{2x^2}{(x-1)^2}
$$

$$
\begin{align*}
\lim_{x\to\infty}f(x)=&\lim_{x\to\infty}\frac{2x^2}{(x-1)^2}&=\frac{\infty}{\infty}\\
\lim_{x\to\infty} \underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}& \lim_{x\to\infty}\frac{4x}{x(x-1)^2}&=\frac{\infty}{\infty}\\  
\lim_{x\to\infty} \underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}& \lim_{x\to\infty}\frac{4}{2}&=2
\end{align*}
$$

$$
\begin{align*}
\lim_{x\to-\infty}f(x)=&\lim_{x\to-\infty}\frac{2x^2}{(x-1)^2}&=\frac{-\infty}{-\infty}\\
\lim_{x\to-\infty} \underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}& \lim_{x\to-\infty}\frac{4x}{x(x-1)^2}&=\frac{-\infty}{-\infty}\\  
\lim_{x\to-\infty} \underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}& \lim_{x\to-\infty}\frac{4}{2}&=2
\end{align*}
$$

## I'Hospital

Zähler und nenner Funktion werden getrennt voneinander abgeleitet

wenn ableitung $\frac{0}{0}$ oder $\frac{\infty}{\infty}$ ergibt

wird die nenner und zähler funktion abgeleitet und dann erneut gelößt

$$
\lim_{x\to x_0}\frac{g(x)}{h(x)}=\lim_{x\to x_o}\frac{g'(x)}{g'(x)} \quad ...
$$

Es gibt auch ausnahmen wo es nicht geht

bsp.

(Ln Kann nicht in den Negativen bereich gehen)

$$
\begin{align*}
\lim_{x\to\infty}\frac{\ln x}{x}&\\
\lim_{x\to\infty}\frac{\ln x}{x} &= \frac{\infty}{\infty}\\
\lim_{x\to\infty}\frac{\ln x}{x} &\underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}\lim_{x\to\infty}\frac{\frac{1}{x}}{1}=\lim_{x\to\infty}\frac{1}{x}=\frac{1}{\infty}=0^+
\end{align*}
$$

---

$$
\begin{align*}
  \lim_{x\to0}\frac{e^x-1}{x} \underset{L'H}{\overset{\mathrm{\frac{0}{0}}}{=}} \lim_{x\to0}\frac{e^x}{1}= \lim_{x\to0}e^x  =1
\end{align*}
$$

## KuvenDiskussion  $e$ funktion

### Was ist $e$ Funktion

Fnuktion die $e^x$ enthält

$$
f(x)=e^x
$$

Die allgemeine e-funktion unterschreitet die X achse niemals und nur wenn eine y achsen verschiebung vor liegt

### Symetrie

Efinktionen besitzen keine Symetrie

$$
f(-x)=f(x)\\
f(x)=(x+1)*e^x\\
f(-x)=(-x+1)*e^{-x}=\frac{(1-x)}{e^x} \neq f(x)
$$
$$
-f(x)=-(\frac{1-x}{e^x})=\frac{-1+x}{e^x}\neq f(x)\\
\implies KEINE \quad Symetrie
$$
### Nullstellen

$$
f(x)=0\\
0=\underbrace{(x+1)}_{=-1}*\underbrace{e^x}_{>0}
$$

$$
\text{Fall 1.}:x+1 =0 \implies x_1=-1 \implies einfache NST(-1|0)\\
\text{Fall 2.}:e^x =0 \implies e^x>0 \implies \text{Keine Nst}
$$

### Vorzeichen Verteilung

<svg xmlns="http://www.w3.org/2000/svg">
  <rect x="20" y="55" width="300" height="3" fill="rgb(0, 0, 0)" />
  <rect x="20" y="107" width="300" height="3" fill="rgb(0, 0, 0)" />
  <rect x="65" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="70" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="150" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="220" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <text textLength="21" font-size="38" x="35" y="50" fill="rgb(0, 0, 0)">x</text>
  <text textLength="34" font-size="25" x="26" y="80" fill="rgb(0, 0, 0)">(x+1)</text>
  <text textLength="34" font-size="25" x="26" y="105" fill="rgb(0, 0, 0)">e^x</text>
  <text textLength="34" font-size="25" x="26" y="130" fill="rgb(0, 0, 0)">f(x)</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="170" y="50" fill="rgb(0, 0, 0)">-1</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="80" fill="rgb(0, 0, 0)">-</text>
  <text textLength="35" font-size="30" x="180" y="80"  fill="rgb(0, 0, 0)">0</text>
  <text textLength="35" font-size="30" x="235" y="80" fill="rgb(0, 0, 0)">+</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="105" fill="rgb(0, 0, 0)">+</text>
  <text textLength="35" font-size="30" x="235" y="105" fill="rgb(0, 0, 0)">+</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="130" fill="rgb(0, 0, 0)">-</text>
  <text textLength="35" font-size="30" x="235" y="130" fill="rgb(0, 0, 0)">+</text>
</svg>

$$
\text{für } > -1: f(x)>0\\
\text{für } < -1: f(x)<0
$$

### Y-achsen Abschnitt

$$
f(0)=(0+1)*e^0=1*1=1\implies S_y(0|1)
$$

### Asymtoten

$$
\lim_{x\to-\infty}(x+1)*e^x=-\infty*0= \lim_{x\to-\infty}\frac{(x+1)}{e^{-x}} \underset{L'H}{\overset{\mathrm{\frac{\infty}{\infty}}}{=}}\lim_{x\to\infty}\frac{1}{-e^{-x}}=\frac{1}{-\infty}=0^-\\
A_1:y=0\\
\lim_{x\to\infty}(x+1)*e^x=\infty*\infty=\infty\implies \text{Keine Weitere Asy.}
$$

### Abletungen

Ableitung  von $e^x \implies e^x$

$$
\begin{align*}
f(x)&=(x+1)*e^x\\
f'(x)&=1*e^x+(x+1)*e^x\\
&e  \text{ Ausklammern} \\
f'(x)&=e^x(1+(x+1))\\
&\text{Zusammenfassen}\\
f'(x)&=e^x(x+2)\\
f'(x)&=(x+2)*e^x\\
\end{align*}
$$

zweite

$$
f''(x)=1*e^x+(x+2)*e^x\\
f''(x)=e^x(1+(x+2))\\
f''(x)=(x+3)*e^x
$$

### Monitonoieverhalten

$$
f'(x)=(x+2)*e^x\\
f'(x)=0\\
0=\underbrace{(x+2)}_{=-2}*\underbrace{e^x}_{>0}\\
x_2=-2
$$

<svg xmlns="http://www.w3.org/2000/svg">
  <rect x="20" y="55" width="300" height="3" fill="rgb(0, 0, 0)" />
  <rect x="20" y="107" width="300" height="3" fill="rgb(0, 0, 0)" />
  <rect x="65" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="70" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="150" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="220" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <text textLength="21" font-size="38" x="35" y="50" fill="rgb(0, 0, 0)">x</text>
  <text textLength="34" font-size="25" x="26" y="80" fill="rgb(0, 0, 0)">(x+2)</text>
  <text textLength="34" font-size="25" x="26" y="105" fill="rgb(0, 0, 0)">e^x</text>
  <text textLength="34" font-size="25" x="26" y="130" fill="rgb(0, 0, 0)">f'(x)</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="170" y="50" fill="rgb(0, 0, 0)">-2</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="80" fill="rgb(0, 0, 0)">-</text>
  <text textLength="35" font-size="30" x="180" y="80"  fill="rgb(0, 0, 0)">0</text>
  <text textLength="35" font-size="30" x="235" y="80" fill="rgb(0, 0, 0)">+</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="105" fill="rgb(0, 0, 0)">+</text>
  <text textLength="35" font-size="30" x="235" y="105" fill="rgb(0, 0, 0)">+</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="130" fill="rgb(0, 0, 0)">-</text>
  <text textLength="35" font-size="30" x="235" y="130" fill="rgb(0, 0, 0)">+</text>
  <text textLength="50" font-size="20" x="160" y="130" fill="rgb(0, 0, 0)">VZW</text>
</svg>

$$
\qquad\\
I_1 ]-\infty;-2[ FSM\\
I_2 ]-2;\infty[ SSM
$$

### Extrempunkte

$$
TIP(-2|f(-2)) \implies TIP(-2|-1,34)\\
$$

### Krümmungsverhalten

$$
f''(x)=0\\
0=\underbrace{(x+3)}_{=-3}*\underbrace{e^x}_{>0}\\
x_1=-3 \implies NST_3(-3|0)
$$


<svg xmlns="http://www.w3.org/2000/svg">
  <rect x="20" y="55" width="300" height="3" fill="rgb(0, 0, 0)" />
  <rect x="65" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="70" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="150" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <rect x="220" y="20" width="3" height="160" fill="rgb(0, 0, 0)" />
  <text textLength="21" font-size="38" x="35" y="50" fill="rgb(0, 0, 0)">x</text>
  <text textLength="34" font-size="25" x="26" y="100" fill="rgb(0, 0, 0)">f''(x)</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="170" y="50" fill="rgb(0, 0, 0)">-3</text>
  <!-- 1-->
  <text textLength="35" font-size="30" x="100" y="80" fill="rgb(0, 0, 0)">-</text>
  <text textLength="35" font-size="30" x="180" y="80"  fill="rgb(0, 0, 0)">0</text>
  <text textLength="35" font-size="30" x="235" y="80" fill="rgb(0, 0, 0)">+</text>
  <text textLength="50" font-size="20" x="160" y="130" fill="rgb(0, 0, 0)">VZW</text>
</svg>

$$
I_3 = ]-\infty;-3 [ \text{Rechts Gekrm}\\
I_4 = ]-3;\infty [ \text{Links Gekrm}\\
$$

### Wendepunkte

$$
\implies WEP(-3|f(-3)) \implies WEP(-3|0,1)
$$
