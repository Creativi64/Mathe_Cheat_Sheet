# Mathe 3

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Mathe 3](#mathe-3)
  - [Steckbrief aufgaben Berechnen](#steckbrief-aufgaben-berechnen)
    - [Allgemeine Funktion](#allgemeine-funktion)
      - [Symetrie](#symetrie)
    - [Bedingungen ermitteln](#bedingungen-ermitteln)
    - [Gleichungssystem lösen](#gleichungssystem-lösen)
    - [Funktion aufstellen](#funktion-aufstellen)
    - [Beispiele](#beispiele)
  - [Extremwert aufgaben](#extremwert-aufgaben)
    - [Haupt Bedingung](#haupt-bedingung)
    - [Nebenbedingungen](#nebenbedingungen)
    - [Zielfunktion](#zielfunktion)
    - [Definitionsbereich festlegen](#definitionsbereich-festlegen)
    - [Extremwerte der Funktion bestimmen](#extremwerte-der-funktion-bestimmen)

<!-- /code_chunk_output -->

## Steckbrief aufgaben Berechnen

### Allgemeine Funktion

Meist direkt angegeben oder In grad angegeben

Bsp. Grad 4
$$f(x)= ax^4+bx^3+cx^2+dx+e$$

Bsp. Grad 3
$$f(x)= ax^3+bx^2+cx+d$$

bsp.

gegebene Funktion

$$f(x)= ax^4+bx^3+cx^2+dx+e$$

$$D_f=[-15;15] \text{und } a \neq 0 ,b,c,d,c \in \mathbb{R} $$

#### Symetrie

 Wenn Eine Symmetrie vorhanden ist

 Symmetrisch zur Y-Achse -> Alle mit ungeraden Exponenten werden weggestrichen

 Symmetrisch zum Ursprung -> alle mit Geraden Exponenten werden weggestrichen

bsp.

symetrisch zur y-achse

$$
f(x)= ax^4+bx^3+cx^2+dx+e \to f(x)= ax^4+bx^2+c
$$

### Bedingungen ermitteln

es bietet sich an gleich die Ableitungen der Allgemeinen formel zu bilden

alle jetzt noch übrig gebliebenen Koeffizienten geben an wie viele Bedingung benötigt werden

Diese Bedingungen sind in der aufgabenstellung angegeben und müssen nur noch entschlüsselt werden

z.B. tief-, hoch- oder wendepunkte etc.

Aus diesen kann festgelegt werden wann die Funktion oder ein Ableitung diesen einen bestimmten wert hat

Tabelle dafür

| nr. | Formulierung                                                  | f(x)        | f'(x)         | f''(x)     |
|-----|---------------------------------------------------------------|-------------|---------------|------------|
| 1   | Scheidet die x-Achse an der $x$                               | $f(x)=0$    | --            | --         |
| 2   | Berührt die x-Achse an der stelle $x$                         | $f(x)=0$    | $f'(x)=0$     | --         |
| 3   | Schneidet die y-Achse an der stelle $y$                       | $f(0)=y$    | --            | --         |
| 4   | Geht durch den Punkt $p(x\mid y)$                             | $f(x)=y$    | --            | --         |
| 5   | hat hoch-/Tiefpunkt an der stelle $x$                         | --          | $f'(x)=0$     | --         |
| 6   | hat hoch-/Tiefpunkt $p(x \mid y)$                             | $f(x)=y$    | $f'(x)=0$     | --         |
| 7   | hat and der stelle $x$ Steigung $m$                           | --          | $f'(x)=m$     | --         |
| 8   | hat Wendepunkt an der stelle $x$                              | --          | --            | $f''(x)=0$ |
| 9   | hat die größte Steigung an der stelle $x$                     | --          | --            | $f''(x)=0$ |
| 10  | $p(x \mid y)$ ist ein Wendepunkt                              | $f(x)=y$    | --            | $f''(x)=0$ |
| 11  | $p(x \mid y)$ ist ein Terrassenpunkt                          | $f(x)=y$    | $f'(x)=0$     | $f''(x)=0$ |
| 12  | berührt den Graphen der Funktion an der stelle $x$            | $f(x)=g(x)$ | $f'(x)=g'(x)$ | --         |
| 13  | die Tangente in $p(x \mid y)$ hat die Steigung $m$            | $f(x)=y$    | $f'(x)=m$     | --         |
| 14  | die Tangente im Wendepunkt $p(x \mid y)$ hat die Steigung $m$ | $f(x)=y$    | $f'(x)=m$     | $f''(x)=0$ |
|     |                                                               |             |               |            |

wenn man mehr Bedingungen gegeben hat als Koeffizienten auszufüllen lässt man diese Bedingungen weg

bsp.

Hochpunkt bei $(0\mid10)$

$$\implies f(x)=10 \text{ und } f'(0)=0$$

Tiefpunkt bei $(-10\mid2)$

$$\implies f(-10)=2 \text{ und } f'(-10)=0$$

### Gleichungssystem lösen

Die Bedingungen nutzen um die fehlenden Informationen zu berechnen

Meist LGS 3x3 oder 2x2 verfahren

bsp.

$c$

$$
f(0)=10\\
\implies a*0^4+b*0^2+c =10 \\
c=10
$$

$\text{I}$

$$
f(-10) =2 \\
\begin{align*}
\implies a*(-10)^4+b*(-10)^2+10&=2 & \\
10000a+100b+10&=2 &|-10 \\
\text{I }:10000a+100b&=-8
\end{align*}
$$

$ b$

$$
f'(-10)=0 \\
\begin{align*}
\implies 0 &= 4*a*(-10)^3+2*b*(-10) \\
0 &=-4000a-20b &|+4000a\\
4000a&=-20b &|:(-20) \\
-200a&=b&
\end{align*}
$$

$b \text{ in I} \to a$

$$
10000a+100*(200a) = -8 \\
a= \frac{1}{1250}
$$

$a \text{ in } b \to b$

$$
-200*(\frac{1}{1250})=b \\
-\frac{4}{25}=b
$$

### Funktion aufstellen

Die berechneten informationen jetzt in die formel einseten und man hat die gesuchte formel

bsp.

$$
f(x)=\frac{1}{1250}x^4-\frac{4}{25}x^2+10
$$

### Beispiele

<http://www.arndt-bruenner.de/mathe/scripts/steckbrief.htm>

Graph dritten gerades besitzt ein Extrempunkt $E(4\mid0)$ schneidet die y-achse in punkt $P(0\mid3)$ und an der stelle $x_w =\frac{7}{3}$ einen Wendepunkt

grundform

$$
f(x)= ax^3+bx^2+cx+d
$$

$$
f'(x)= 3ax^2+2bx+c
$$

$$
f''(x)= 6ax+2b
$$


bedingungen

vier gesucht eine gegeben

1. extempunkt bei $E(4 \mid0)$
$$
f(4)=0,  f'(4)=0
$$

2. schneidet y-achse in punkt $p(0\mid3)$

$$
f(0)=3
$$

$$d=3$$

3. Wendepunkt an stelle $x_w =\frac{7}{3}$

$$
f''(\frac{7}{3})=0
$$

lösen

I
$$
\begin{align*}
  f(4)&=0; &\\
  0&=a(4)^3+b(4)^2+c(4)+3 &\\
  0&=64a+16b+4c+3 &|-3 |*(-1)\\
  3&=-64a-16b-4c
\end{align*}
$$
II
$$
\begin{align*}
  f'(4)&=0\\
  0&=3a(4)^2+2b(4)+c\\
  0&=48a+8b+c &|-c\\
  -c&=48a+8b &| * (-1) \\
  c&=-48a-8b
\end{align*}
$$

III
$$
\begin{align*}
f''(\frac{7}{3})&=0 \\
  0&=6a(\frac{7}{3})+2b \\
  0&=14a+2b &|-2b | \backslash (-2)\\
  b&= -7a
\end{align*}
$$
  

II in I
II'
$$
\begin{align*}
   3&=-64a-16b-4(-48a-8b) \\
   3&=-64a-16b+192a+32b \\
   3&=128a +16b \\
  \end{align*}
$$

b in II'

$$
\begin{align*}
 3&=128a +16(-7a) \\  
 3&=128a -112a \\  
 3&=16a \\  
 \frac{3}{16}&=a \\  
\end{align*}
$$

a in III

$$
\begin{align*}
  b&=-7(\frac{3}{16})\\
  b&=-\frac{21}{16}
\end{align*}
$$

a,b in I

$$
\begin{align*}
  3&=-64(\frac{3}{16})-16(\frac{21}{16})-4c \\
  3&=-12+21 -4c &|+4c|-3\\
  4c&=6&|\backslash 4 \\
  c&=\frac{3}{2}\\
\end{align*}
$$

$$
f(x)= \frac{3}{16}x^3-\frac{21}{16}x^2+\frac{3}{2} x+3
$$

## Extremwert aufgaben

optimieren eines wertes der erreicht werden kann in abhänigkeit zu gegebeheiten

### Haupt Bedingung

Die formel die in optimiert wird

stellte das da wo von die größe ermittelt werden will

z.b.

eine größt mögliche fläche innerhalb eines quadrates mit oben rechts fehlenende ecke 1 x 0,6 links nur noch 0,4 und oben nur noch 0,6

$a$ ist die lange die von der Unterseite abgezogen wird um ein neues möglichst großes rechteck zu bilden die höhe ist von 0 bis 0,6 noch frei

es sind die punkte $D(0,6|0,6)$ und $C(1,0,4)$ die die beiden ecken der fehlenden ecke markieren und $P$ der gesucht wird

als fromel ergibt sich

$$
A=a*b \\
A(a;y)=(1-a)*y \\\
\\
P(1-a|y)
$$

gesucht wird jetzt der größtmögliche wert für A in Abhängigkeit zu $a$ und $y$

### Nebenbedingungen

$P$ liegt auf der geraden der punkte $D$ und $C$ und können somit eine formel aufstellen mit der wir $y$ auflösen können damit nur noch a als variable übrigbleibt

grundform

$$
y=m*x+t
$$

steigung $m$

$$
m= \frac{\triangle y}{\triangle x} =\frac{y_C-y_D}{x_C-x_D} = \frac{0,4-0,6}{1-0,6}=-\frac{1}{2} \\
\implies y=-\frac{1}{2}x+t
$$

$D$ in y einsetzen

$$
0,6=-\frac{1}{2}0,6+t \\
t=0,9
$$

$$
g(x)=-\frac{1}{2}x+0,9
$$
btw $x$ = $a$

### Zielfunktion

$g(x)$ in Hauptbedingung
$$
\begin{align*}
A(a) & = (1-a)*(-\frac{1}{2}*(1-a)+0,9)\\
&=(1-a)*(-\frac{1}{2}+\frac{1}{2}a+0,9)\\
&=-0,5a^2+0,1a+0,4
\end{align*}
$$
### Definitionsbereich festlegen

der definitions berich der bestimmenden variable hier $a$

der kleinst mögliche wert ist 0 (man zeiht von der seite nix ab) und der gröst mögliche ist 1 (da wir von der seie 1 lang ist und negativ keine seinn macht)

also

$$
\mathbb{D}[0;1]
$$

### Extremwerte der Funktion bestimmen

Extremwerte der Funktion bestimmen, möglicher max $a$ wert und minimal $a$ wert also nullstellen der ersten abletung bestimmen

$$
A(a)= -0,5a^2+0,1a+0,4\\
A'(a) = -a+0,1
$$

$$
\begin{align*}
A'(a)&=0\\
0&=-a+0,1 \\
a&=0,1 \in \mathbb{D}
\end{align*}
$$

<svg xmlns="http://www.w3.org/2000/svg">
    <rect x="21" y="67" width="299" height="4" fill="rgb(0, 0, 0)" />
    <rect fill="rgb(0, 0, 0)" x="65" y="18" width="4" height="101" />
    <rect x="72" y="18" width="4" height="97" fill="rgb(0, 0, 0)" />
    <rect x="161" y="18" width="3" height="101" fill="rgb(0, 0, 0)" />
    <rect x="216" y="20" width="3" height="101" fill="rgb(0, 0, 0)" />
    <text font-size="38" textLength="21" fill="rgb(0, 0, 0)" x="35" y="49.9">a</text>
    <text font-size="25" textLength="33.9" fill="rgb(0, 0, 0)" x="25.6" y="96.8">A'(a)</text>
    <text textLength="38.9" font-size="41" x="122.6" y="102.2" fill="rgb(0, 0, 0)">+</text>
    <text textLength="38.9" font-size="41" x="233.6" y="101.2" fill="rgb(0, 0, 0)">-</text>
    <text textLength="43.2" font-size="25" x="168.9" y="49.8" fill="rgb(0, 0, 0)">0,1</text>
    <text fill="rgb(0, 0, 0)" font-size="25" x="174.9" y="98.8" textLength="23.2">0</text>
    <path stroke="rgb(0, 0, 0)" d="M 270 118 C 270 118 102 16 102 16" fill="none"/>
</svg>

da ein Vorzeichen wechsele stat finden ist dieser Punkt das relative maximum

$$
A(0,1)=-0,5(0,1)^2+0,1(0,1)+0,4\\
A(1,1)=0,405
$$

Rand Untersuchung der Funktion
$$
A(0)=-0,5(0)^2+0,1(0)+0,4\\
A(0)=0,4
$$

$$
A(1)=-0,5(0,1)^2+0,1(0,1)+0,4\\
A(1)=0
$$

Relative maximum ist auch das maximale maximum