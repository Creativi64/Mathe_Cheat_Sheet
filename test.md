# Mathe  WIP

## ZahlenBereiche

$$
\gets-\frac{}{4}-\frac{}{3}-\frac{}{2}-\frac{}{1}-\frac{}{0}-\frac{}{-1}-\frac{}{-2}-\frac{}{-3}-\frac{}{-4}-\to
$$

|Name|Zeichen|Bereich|
|---|---|---|
|Natürlichezahlen|$\mathbb{N}$|{1 ; 2 ; 3 ; ... ; 100 ; ...}|
|" inkl. "0"|$\mathbb{N}$<sub>0</sub>|{0 ; 1 ; 2 ; ...}|
|GanzeZahlen|$\mathbb{Z}$|{... ; -2 ; -1 ; 0 ; 1 ; 2 ; ...}|
|RationaleZahlen|$\mathbb{Q}$|{... ; -1 ; -0,5 ; -$\frac{1}{12}$ ; -$\frac{1}{24}$ ; 0 ; $\frac{1}{4}$ ; $\frac{3}{4}$ ; $\frac{1}{3}$ ; ...}|
|ReelleZahlen|$\mathbb{R}$|{... ; $\pi$ ; $\pm\sqrt{2}$ ; 0 ; 1 ; $\sqrt{3}$ ; $\frac{1}{3}$ ; ...}|
|KomplexeZahlen|$\mathbb{C}$|{... ; ($-5+3\sqrt{i}$) ; -6,75 ; $\mathrm{i}$ ; 0 ; 1 ; ...}|
|Primzahlen|$\mathbb{P}$|{2 ; 3 ; 5 ; 7 ; 11 ; 13 ; 17 ; 19 ; 23 ; 29 ; 31 ; ...}|

## Brüche auf gleichen NennerBringen

1. Addition
$$
\frac{a}b{} +\frac{c}{d}=\frac{a*d}{b*d}+\frac{c*b}{d*b}=\frac{a*d+c+b}{b*d}
$$
2. Subtraktion
$$
\frac{a}{b}-\frac{c}{d}=\frac{a*d}{b*d}-\frac{c*d}{d*b}=\frac{a*d-c*b}{b*d}
$$
3. Multiplikation
    - Mit Ganzer Zahl
    $$
    \frac{a}{b}*c=\frac{a*c}{b}
    $$
    - Mit Bruch
    $$
    \frac{a}{b}*\frac{c}{d}=\frac{a*c}{b*d}
    $$
4. Division
    - Mit Ganzer Zahl
    $$
    \frac{a}{b}/c=\frac{a}{b*c}9
    $$
    - Mit Bruch
    $$
    \frac{a}{b}/\frac{c}{d}=\frac{a}{b}*\frac{d}{c}=\frac{a*d}{b*c}
    $$

## Koordianten system
Zwei Felder 1cm
<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
		<!-- Linie des Funktionsgraphen -->
		<path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" />
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="360" y="220" fill="darkslategray">(0,0)</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text>
</svg>
</div>

## Kartesisches Kordinaten System
Zwei Felder 1cm
<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
		<!-- Linie des Funktionsgraphen -->
		<!-- <path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" /> -->
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="360" y="220" fill="darkslategray">(0,0)</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="440" y="195" fill="#999">X-Achse/Abzisse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="60" fill="#999">Y-Achse/Ordinate</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<!-- <text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text> -->
        <!-- <circle cx="250" cy="100" r="4" fill="#c32e04"></circle>
        <circle cx="250" cy="300" r="4" fill="#c32e04"></circle>
        <circle cx="450" cy="100" r="4" fill="#c32e04"></circle>
        <circle cx="450" cy="300" r="4" fill="#c32e04"></circle> -->
        <text x="450" y="100" fill="darkslategray">I</text>
        <text x="250" y="100" fill="darkslategray">II</text>
        <text x="250" y="300" fill="darkslategray">III</text>
        <text x="450" y="300" fill="darkslategray">IV</text>
</svg>
</div>

|||
|--|--|
|Ursprung | Schnittpunkt beider achsen|
|Abszisse|X-achse, Horizontale achse|
|Ordinate|y-achse, Vertikale achse|
|Quadrant|Von oben rechts im Uhrzeigersinn gehzählt|

## Drei Dimensional

Zwei Felder 1cm
<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
        <!-- z-Achse -->
		<path class="axis" id="z-axis" d="M200,350  L500,50" />
		<!-- Linie des Funktionsgraphen -->
		<!-- <path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" /> -->
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="350" y="215" fill="darkslategray">(0,0)</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
        <!-- Beschriftung Y-Achse -->
		<text id="z-label" x="390" y="140" fill="#999">Z-Achse</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<!-- <text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text> -->
        <path stroke="#ff3300" d="M330,220  L350,200" />
        <path stroke="#009c2f" d="M330,220  L410,220" />
        <path stroke="#001eff" d="M410,220  L410,240" />
        <circle cx="410" cy="240" r="4" fill="#c32e04"></circle>
        <text x="415" y="250" fill="darkslategray">(0,0)</text>
        <text id="x-label" fill="#009c2f" x="360" y="230" fill="#999">4</text>
		<text id="y-label" fill="#001eff" x="165" y="95" fill="#999">-1</text>
		<text id="z-label" fill="#ff3300" x="220" y="140" fill="#999">2</text>
</svg>
</div>

P(2|4|-1)

# Funktion und Relation

- Funktion
    - Nur Ein Wert von y Kann Ein x Wert zugewiesßen werden
- Realtion
    - Es Können Mehrere y werte ein x Wert zugewiesen werden

### Funktion

$$ F/f: x\mapsto f(x) = Y= 2x $$

FunktionsName : $$F/f $$ 

Argumentations Variable
$$x$$
FunktionsWert
$$f(x)$$
FunktionsGleiung
$$x\mapsto(x)=y=2x$$
Funktionsterm
$$y=2x$$

Zwei Felder 1cm
<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
		<!-- Linie des Funktionsgraphen -->
		<!-- <path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" /> -->
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="360" y="220" fill="darkslategray">(0,0)</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<!-- <text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text> -->
        <path d="M 330 130 q 50 200 100 0" stroke="blue" stroke-width="1" fill="none" />
        <path stroke="red" id="y-axis" d="M395,200 v20" />
		<circle cx="395" cy="200" r="2" fill="#c32e04"></circle>
		<circle cx="395" cy="220" r="2" fill="#c32e04"></circle>
		<text x="395" y="198" fill="darkslategray">X</text>
		<text x="395" y="230" fill="darkslategray">Y</text>
</svg>
</div>

### Relation 

<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
		<!-- Linie des Funktionsgraphen -->
		<!-- <path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" /> -->
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="360" y="220" fill="darkslategray">(0,0)</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<!-- <text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text> -->
        <path d="M 470 130 q -200 50 0 100" stroke="blue" stroke-width="1" fill="none" />
        <path stroke="red" id="y-axis" d="M435,140 v80" />
		<circle cx="435" cy="140" r="2" fill="#c32e04"></circle>
		<circle cx="435" cy="220" r="2" fill="#c32e04"></circle>
		<circle cx="435" cy="200" r="2" fill="#c32e04"></circle>
		<text x="435" y="198" fill="darkslategray">X</text>
		<text x="435" y="235" fill="darkslategray">Y1</text>
		<text x="435" y="135" fill="darkslategray">Y2</text>
</svg>
</div>

<iframe src="https://www.geogebra.org/calculator/rn5dnvqe?embed" width="90%" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

Tablelle:
|Y|-1|0|1|2|3|
|--|--|--|--|--|-|
|fx)=y|-2|0|2|4|6|

## Realtion Funktion?

<iframe src="https://www.geogebra.org/calculator/tvy6rqrv?embed" width="90%" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

$$x = 1,5 \to f(1,5)= \tilde{+} 1,32$$
$$x = 1,5 \to g(1,5)= \tilde{-} 1,32$$

<iframe src="https://www.geogebra.org/calculator/tqg39tbg?embed" width="90%" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

$$
x=1,5 \begin{cases}
    Y_1 = \tilde{+}1,32 \\    Y_2 = \tilde{-}1,32
  \end{cases}
$$

## Ursprungsgeraden

Verlaufen durch den Ursprung(0,0)

$$
y=mx\\z.b.\to f:x \mapsto y=3*x
$$

### Lange Bezeichnung

Stehen $g$ und $f$ senkrecht($\perp$) zueinander?

<iframe src="https://www.geogebra.org/calculator/tc2q65mm?embed" width="90%" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

$$
g\perp f \iff
m1*m2 = -1
$$

## Steigung

$$
\bigtriangleup = Delta
$$
$$
y= m*x \quad   |:x  \\\frac{\bigtriangleup Y}{\bigtriangleup X}=m\\\frac{1,5}{3}=0,5
$$

<div style="width:90%">
<svg viewbox="0 0 700 400">
<defs>
<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
</pattern>
<!-- eine Pfeilspitze -->
<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
</marker>
</defs>
<!-- Karo-Muster -->
<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
<!-- Ursprungspunkt -->
<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
<!-- X-Achse -->
<path class="axis" id="x-axis" d="M0,200 h695" />
<!-- Y-Achse -->
<path class="axis" id="y-axis" d="M350,400 v-395" />
<!-- Linie des Funktionsgraphen -->
<path id="functionGraph" d="M50,350 L650,50" stroke="#0f0" />
<!-- Beschriftung des Ursprungspunktes -->
<text x="315" y="195" fill="darkslategray">(0,0)</text>
<!-- Beschriftung X-Achse -->
<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
<!-- Beschriftung Y-Achse -->
<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
<path stroke="blue" id="y-axis" d="M450,150 v30" />
<path stroke="blue" id="y-axis" d="M390,180 v20" />
<path stroke="green" id="y-axis" d="M350,200 h40" />
<path stroke="green" id="y-axis" d="M390,180 h60" />
<text x="420" y="190" fill="darkslategray">X=3</text>
<text x="455" y="170" fill="darkslategray">Y=1,5</text>
<text x="360" y="210" fill="darkslategray">X=2</text>
<text x="392" y="192" fill="darkslategray">y=1</text>
</svg>
</div>

$$
m = \frac{\bigtriangleup Y}{\bigtriangleup X}= \frac{y_2-y_1}{x_2-x_1}
$$
$$
m= \frac{0,75}{1,5}=\frac{1}{2}=0,5
$$
Die gerade Fällt
$$m>0$$
Die Gerade fällt
$$m<0$$

## Y Achsenabschnitt

$$
\begin{align*}
y &= mx + t \\mx+t&=0 \quad|-t \\mx&=-t \quad|:m \\x&=\frac{-t}{m}\\\end{align*}
$$

Der y-Achsenabschnitt gibt den schnittpunkt der gerade mit der y-Achse an 
$$
S_y(o|t)
$$

## Nullstelle

$$X_0$$
Die Stelle An der der Graph die X-Achse schneidet ist die nullstelle

$$\text{NST}(-\frac{-t}{m})$$

### Berechnen von Nullstellen

$$
f(x)=0=x-2 \quad \Rightarrow x-2=0|+2 \quad \Leftrightarrow \quad x=2 \quad \to \text{NST}(2|0)
$$

## Funktions Gleichungs Darstellungsformen

|Normale,Explizierte Form| Allgemeine, implizite Form|Achsenabschnittsform|
|--|--|--|
|$$y=mx+t$$|$$ax+by+c=0$$|$$\frac{x}{x_0}+\frac{y}{y_0}=1$$|

## Lage Bezeichnungen

||||
|-|-|-|
|Senkrecht|$$f_1\perp f_2$$||
|Parallel|$$f_1\parallel f_2$$||
|identisch|$$f_1= f_2$$|||
|schneiden|$$ m_1 \neq m_2$$||

## Gleichungstypen

|||
|--|--|
|Lineare Gleiung|$$2x-3=3x+5$$|
|Quadratische|$$x^2-2x=-1$$|
|Trigonometrische/|$$3\sin(\frac{x}{4})=2$$|
|Bruchgleicung|$$\frac{x^4-2x}{2x+1}=\frac{1}{x}$$|
|Exponential|$$2^{4x}=3$$|
|betragsglechungen|$$\mid x-3 \mid =4$$|
|Wurzel glechung|$$\sqrt{x^2+8x+4}=1$$|

## Mengenbezeichnungenn

Die Menge der Werte von X, die man  in die gleichung einsetzen kann, nennt mann **Grundmenge** $\to \mathbb{G}$

Die Menge der werte von x, für die eine wahre aussage entsteht, nennt man die **Lösungsmenge** $\to \mathbb{L}$

es gilt immer $\mathbb{L} \subseteq \mathbb{G}$, ($\subseteq$ ist teilmenge von)

$$
\begin{align*}
x-2&=-2 |+2 \\x&=-3
\end{align*}
$$
$$
\begin{align*}
\mathbb{G} = \mathbb{Q} \quad \Rightarrow \mathbb{L}&=\{-3\}\\\mathbb{G} = \mathbb{Z} \quad \Rightarrow \mathbb{L}&=\{-3\}\\\mathbb{G} = \mathbb{N} \quad \Rightarrow \mathbb{L}&=\{\}/\emptyset  \quad \text{,da}-3 \notin \mathbb{N}
\end{align*}
$$

## Äquivalenzumformungen

Zwei gleichungen sind equivalent zueinander wenn sie die gleiche lösungs- und grundmenge haben

$$
x-2=-5 \Leftrightarrow x-1=-4 \Leftrightarrow 3x=-9
$$
### Beispiele Für umformungen

- Addition

$\mathbb{L}\{-3\}$


$$
\begin{align*}
x-2 &= -5 \quad|+2\\x &= -3
\end{align*}
$$
- Multiplikation

$\mathbb{L}\{-3\}$

$$
\begin{align*}
-\frac{1}{3} x &= 1 \quad|-(-3)\\x &= -3
\end{align*}
$$


- Division

$\mathbb{L}\{-3\}$

$$
\begin{align*}
3*x &= -9 \quad|:3\\x &= -3
\end{align*}
$$

## Lineare Ungleichungen
$\mathbb{G=Q}_{0+}$

$$
\begin{align*}
x+2&<3 \qquad |-2 \\x &< 1 \\\mathbb{L}=[0;1]_\mathbb{Q0+}&=\begin{cases}
    X| X \in _\mathbb{Q0+} \land x < 1
  \end{cases}
\end{align*}
$$

## Regeln

$$
\begin{align*}
-2&<-1 \qquad |*(-1)\\2&>1
\end{align*}
$$

## Lösungmenge

$$
\gets-\frac{
\begin{matrix}
  \\  \gets\\  \\ \end{matrix}
 }{-4}\frac{
\begin{matrix}
  \\  -\\  \\ \end{matrix}
 }{-3}\frac{
\begin{matrix}
  \\  -\\  \\ \end{matrix}
 }{-2}\frac{
\begin{matrix}
  \\  -\\  \\ \end{matrix}
 }{-1}\frac{
\begin{matrix}
  [\\  -\\  [ 
 \end{matrix}
 }{0}\frac{
\begin{matrix}
  -\\  [\\  [
 \end{matrix}
 }{1}\frac{
\begin{matrix}
  -\\  \\  \\ \end{matrix}
 }{2}\frac{
\begin{matrix}
  -\\  \\  \\ \end{matrix}
 }{3}\frac{
\begin{matrix}
  \to\\  \\  \\ \end{matrix}
 }{4}-\to
$$

$ \mathbb{L} = [0-1[$

## Quadratische Funktionen und Gleichungen

Quadratische Gleichung
$$
ax^2+bx+c=0
$$

Quadratische Funktion
$$
f(x)=\quad y=ax^2+bx+c
$$

### Allgemeine Funktion

$$
f(x)= y=ax^2+bx+c \qquad x \in \mathbb{R}; \quad a \in \mathbb{R} \backslash \{0\} ; \quad b,c \in \mathbb{R}
$$

## NomalParabel

$$
g(x)=x^2
$$

<div style="width:90%">
<svg viewbox="0 0 700 400">
	<defs>
			<pattern id="grid" patternUnits="userSpaceOnUse" width="10" height="10" x="0" y="0">
				<path d="M0,0 v10 h10" stroke="#57c4ff" fill="none" />
             </pattern>
			<!-- eine Pfeilspitze -->
			<marker id="markerArrow" markerWidth="130" markerHeight="13" refx="2" refy="6" orient="auto">
				<path d="M0,2 l8,4 l-8,4" fill="none" stroke="#999" stroke-width="1" /> 
            </marker>
		</defs>
		<!-- Karo-Muster -->
		<rect x="0" y="0" width="700" height="400" fill="url(#grid)"></rect>
		<!-- Ursprungspunkt -->
		<circle cx="350" cy="200" r="4" fill="#c32e04"></circle>
		<!-- X-Achse -->
		<path class="axis" id="x-axis" d="M0,200 h695" />
		<!-- Y-Achse -->
		<path class="axis" id="y-axis" d="M350,400 v-395" />
		<!-- Linie des Funktionsgraphen -->
		<!-- <path id="functionGraph" d="M140,400 L540,0" stroke="#0f0" /> -->
		<!-- Beschriftung des Ursprungspunktes -->
		<text x="352" y="213" fill="darkslategray">s(0,0) Ursprung, Hier ScheitelPunkt</text>
		<!-- Beschriftung X-Achse -->
		<text id="x-label" x="640" y="195" fill="#999">X-Achse</text>
		<!-- Beschriftung Y-Achse -->
		<text id="y-label" x="340" y="20" fill="#999">Y-Achse</text>
		<!-- Beschriftung des Funktionsgraphen -->
		<!-- <text>
			<textPath id="graph-label" fill="#0f0" startOffset="20" xlink:href="#functionGraph">f(x)=x+1</textPath>
		</text> -->
        <path d="M 310 120 q 40 160 80 0" stroke="blue" stroke-width="1" fill="none" />
        <!-- <path stroke="red" id="y-axis" d="M435,140 v80" />
		<circle cx="435" cy="140" r="2" fill="#c32e04"></circle>
		<circle cx="435" cy="220" r="2" fill="#c32e04"></circle>
		<circle cx="435" cy="200" r="2" fill="#c32e04"></circle>
		<text x="435" y="198" fill="darkslategray">X</text>
		<text x="435" y="235" fill="darkslategray">Y1</text>
		<text x="435" y="135" fill="darkslategray">Y2</text> -->
</svg>
</div>

$$
\begin{align*}
\text{NST}:f(x)&=0\\
\\
f(x)&=x^2\\
0&=x^2 \quad |\sqrt{}\\0&=|x|
\end{align*}
$$

$$
\text{1.Fall} \geq 0:+x_1=0\Rightarrow\text{NST}(0|0)\\\text{2.Fall} < 0:-x_2=0 \Rightarrow\text{NST}(0|0)\\$$
$\mathbb{D=R}\Rightarrow \mathbb{W=R}^+_0$

## Verhalten Von

$$a$$

$$
a>0 \quad \text{Nach Oben Geöffnet}\\a<0 \quad \text{Nach Unten Geöffnet}
$$

$$
|a| <1 \quad \text{Weiter Geöffnet}\\|a| >1 \quad \text{Enger Geöffnet}
$$

$$
\boxed{|x| =\begin{cases}
    X, \text{wenn} x \geq0\\	-x, \text{wenn} x <0
  \end{cases}
  }
$$

## Verhalten Von

$$c$$

$$
c>0
$$
Der Graph verschiebt sich an der Y achse um $c$ nach oben $S(0;c)$

$$
c<0
$$
Der Graph verschiebt sich an der Y achse um $|c|$ nach oben $S(0;c)$

<iframe src="https://www.geogebra.org/calculator/uazyuep4?embed" width="90%" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

NST: $f$
$$f(x)= 0$$

$$
\begin{align*}
f(x)&=2\\y&=x \\f(x)=0 \iff x^2&=0 \quad |\sqrt{}\\|x|&= \sqrt{0}=0
\end{align*}
$$

1.Fall:

$$x\geq 0:x_1=0 $$
2.Fall:

$$
\begin{align*}
x<0:-x_2&=0 \quad |*-(1)\\x^2&=0
\end{align*}
$$

NST(0|0) doppelte NST

---

NST: $g$

$$
\begin{align*}
g(x)&= x^2-1\\g(x)= 0 \iff x^2-1&=0\quad|+1\\x^2&=1\quad|\sqrt{}\\x_1=1&\quad x_2=-1
\end{align*}
$$

NST $_1$ (1|0)

NST $_2$ (-1|0)

Einfache NST

---

NST: $h$

$$
\begin{align*}
f(x)&=x^2+2\\f(x)=0 \iff x^2+2&=0 \quad |-2\\x^2&=-2\quad|\sqrt{} \\x&=\sqrt{-2}
\end{align*}
$$

$ \text{Keine NST Da} \sqrt{-2} \text{nicht geht}$

---

ende

<style>
svg {
background: white;
border: 1px dotted #3983ab;
width: 95%;
height: 400px;
padding: 0;
position: relative;
}

.axis {
stroke: #999;
marker-end: url(#markerArrow);
}

text {
font-family: verdana;
font-size: 12px;
}

#graph-label {
font-family: "Open Sans", sans;
font-size: 2em;
font-weight: bold;
text-shadow: 0px 0px 1px black;
}

#y-label {
transform: rotate(-90deg);
transform-origin: 363px 38px;
}
#z-label {
transform: rotate(-45deg);
transform-origin: 363px 38px;
}

label {
cursor: pointer;
}

input[name="a"],
input[name="c"] {
width: 4em;
}

fieldset,
legend {
background: white;
border: 1px solid black;
border-radius: 0.2em;
}

legend {
padding: 0.2em 1em;
}

fieldset p {
text-align: center;
}
</style>
