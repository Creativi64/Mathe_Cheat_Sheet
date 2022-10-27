# Mathe 4

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Mathe 4](#mathe-4)
  - [Vektoren](#vektoren)
    - [Darstellung](#darstellung)
      - [Schreibweise](#schreibweise)
      - [Direktere darstellung](#direktere-darstellung)
    - [betrang/ länge berechnen von Vector](#betrang-länge-berechnen-von-vector)
    - [Winkel Zwischen Zwei Vectoren Berechnen](#winkel-zwischen-zwei-vectoren-berechnen)
    - [Umrechnung](#umrechnung)
      - [zwei Punnkten zu x,y Richtung](#zwei-punnkten-zu-xy-richtung)
      - [x,y Richtung zu Länge und winkel](#xy-richtung-zu-länge-und-winkel)
      - [Länge und winkel zu x,y Richtung](#länge-und-winkel-zu-xy-richtung)
      - [zu x,y Richtung zu zwei Punnkten](#zu-xy-richtung-zu-zwei-punnkten)
    - [Rechnen mit Vectoren](#rechnen-mit-vectoren)
      - [Addition und Substraktion](#addition-und-substraktion)
      - [Rechengesetze](#rechengesetze)
      - [Skalar multiplkation](#skalar-multiplkation)
    - [Vektor typen](#vektor-typen)
      - [Einheitsverktor](#einheitsverktor)
      - [Gegensvektor](#gegensvektor)
      - [Ortsvektor](#ortsvektor)
      - [Skalar](#skalar)
    - [Kollineare und Komplanare Vektoren](#kollineare-und-komplanare-vektoren)
      - [Kollinear](#kollinear)
      - [Komplanar](#komplanar)
    - [Basisverktoren](#basisverktoren)
    - [Skalar produkt](#skalar-produkt)
    - [Kreuzprodukt](#kreuzprodukt)
      - [rechte hand regel](#rechte-hand-regel)
      - [betrag](#betrag)
      - [Rechenregeln](#rechenregeln)
      - [rechnen](#rechnen)
      - [Fläche](#fläche)
        - [Fläche Parallelogramm](#fläche-parallelogramm)
        - [Fläche Dreiceck](#fläche-dreiceck)
      - [Vloumen](#vloumen)
        - [Spat](#spat)
        - [Prisma](#prisma)
        - [4-Seitige Pyramide](#4-seitige-pyramide)
        - [Tetraeder 3-Seitige Pyramide](#tetraeder-3-seitige-pyramide)
  - [Geraden](#geraden)
    - [Aufstellen](#aufstellen)
    - [prüfen ob ein punkt auf der geraden liegt](#prüfen-ob-ein-punkt-auf-der-geraden-liegt)
    - [Durch stoß punkt](#durch-stoß-punkt)
    - [Koordinaten gleichung](#koordinaten-gleichung)
  - [Parameter From](#parameter-from)
    - [Normalen Form](#normalen-form)
    - [Umrechnung $\mathbb{R}^2$](#umrechnung-mathbbr2)
      - [Parameterform in Normalenform](#parameterform-in-normalenform)
      - [Normalenform in koordinatenform](#normalenform-in-koordinatenform)
      - [koordinatenform in normalenform](#koordinatenform-in-normalenform)
      - [Normalenform in Paramterform](#normalenform-in-paramterform)
  - [Ebenen](#ebenen)

<!-- /code_chunk_output -->

## Vektoren

Vektor

Ein in Pfeilen angegebene Richtung oder Verbindungsweg zwischen zwei punkten

die Pfeile parallel, gleich orientiert und gleich lang sind

### Darstellung

#### Schreibweise

immer mit Pfeil über dem Buchstaben nach rechts

$$
\vec{a}\\
$$

Die Großbuchstaben geben hierbei Punkte an

$$
\vec{AB}\\
$$

#### Direktere darstellung

Definition durch die x,y und z werte
$$
\vec{a}=(x|y|z)\\
oder \\
\vec{a}=\begin{pmatrix}
X\\
Y\\
Z
\end{pmatrix}
$$

definition durch x,y Werte

$$
\vec{AB}\\
A=(1;1)\\
b=(2;2)\\
$$

Länge und richhtung

$$
\vec{a}=(2;45°)
$$

### betrang/ länge berechnen von Vector

$$
\vert \vec{a} \vert =\sqrt{{a_1}^2+{a_2}^2...}
$$

### Winkel Zwischen Zwei Vectoren Berechnen

$$
\cos(\varphi)=\frac{a_1*b_1+a_2*b_2 ...}{\vert \vec{a}\vert* \vert \vec{b}\vert}
$$

### Umrechnung

#### zwei Punnkten zu x,y Richtung

$$
A(a_1|a_1)\\
B(b_2|b_2)
$$

$$
\vec{v}=\begin{pmatrix*}
  v_x\\
  v_y
\end{pmatrix*}=\begin{pmatrix*}
  b_1-a_1\\
  b_2-a_2
\end{pmatrix*}
$$

#### x,y Richtung zu Länge und winkel

$$
\vec{v}=(\vert\vec{v}\vert;a)
$$

$$
\vert\vec{v}\vert =\sqrt{{v_x}^2+{v_y}^2}
$$

$$
a=\tan^{-1}(\frac{v_y}{v_x})
$$

#### Länge und winkel zu x,y Richtung

$$
\vec{v}=\begin{pmatrix*}
  v_x\\
  v_y
\end{pmatrix*}
$$

$$
v_x=\vert\vec{v}\vert *\cos(a)\\
v_y=\vert\vec{v}\vert *\sin(a)\\
$$

#### zu x,y Richtung zu zwei Punnkten

benötigt eine vorgegebenen punkt

$$
A(a_1|a_2)
$$

$$
\begin{pmatrix*}
  b_1\\
  b_2
\end{pmatrix*} =\begin{pmatrix*}
  a_1-v_x\\
  a_2-v_y
\end{pmatrix*}
$$

$$
B(b_1|b_2)
$$
### Rechnen mit Vectoren

#### Addition und Substraktion

beliebigerweiterbar

$$
\vec{a}+\vec{b}=\begin{pmatrix*}
  a_x\\
  a_y\\
  a_z
\end{pmatrix*}+\begin{pmatrix*}
  b_x\\
  b_y\\
  b_z
\end{pmatrix*}=\begin{pmatrix*}
  a_x+b_x\\
  a_y+b_y\\
  a_z+b_z
\end{pmatrix*}
$$

$$
\vec{a}-\vec{b}=\begin{pmatrix*}
  a_x\\
  a_y\\
  a_z
\end{pmatrix*}-\begin{pmatrix*}
  b_x\\
  b_y\\
  b_z
\end{pmatrix*}=\begin{pmatrix*}
  a_x-b_x\\
  a_y-b_y\\
  a_z-b_z
\end{pmatrix*}
$$

#### Rechengesetze

kommutativgesetz

$$
\vec{a}+\vec{b}=\vec{b}+\vec{a}
$$

Assoziativgesetz

$$
(\vec{a}+\vec{b})+\vec{c}=\vec{a}+(\vec{b}+\vec{c})
$$

Existenz eines neutralen Elemntes

$$
\vec{a}+\vec{0}=\vec{b}
$$

Existenz inverser Elemente

$$
\vec{a}+(-\vec{a})=\vec{0}
$$

#### Skalar multiplkation

multiplikation eines vectors mit einer reellen zahl (Skalar)

$$
\lambda*\vec{a}=\lambda*\begin{pmatrix*}
  a_x\\
  a_y\\
  a_z
\end{pmatrix*}=\begin{pmatrix*}
  \lambda*a_x\\
  \lambda*a_y\\
  \lambda*a_z
\end{pmatrix*}
$$

---

$$
\lambda =0\\
\lambda*\vec{v}=0*\vec{v}=\vec{0}=\begin{pmatrix*}
 0\\
 0\\
0
\end{pmatrix*}
$$

---

$$
\vec{v} =\vec{0}\\\
\\
\lambda\vec{v} =\lambda*\vec{0}=\vec{0}
$$

---

$$
\vec{v}\neq\vec{0} \And \lambda \neq 0 \\\
\\
\begin{align*}
  \lambda>0& \implies\lambda\vec{v}\uparrow\uparrow\vec{v}\\
  \lambda<0&\implies\lambda\vec{v}\uparrow\downarrow\vec{v}\\
  \lambda\in\mathbb{R}&\implies\lambda\vec{v}||\vec{v}\\
  |\lambda*\vec{v}|&=|\lambda|*|\vec{v}|
\end{align*}
$$

---

$$
\lambda,\mu =\text{Skalare}\\\ \\
\begin{align*}
a)& \quad \lambda*(\mu*\vec{v})=(\lambda*\mu)*\vec{v} \\
b)& \quad (\lambda+\mu)*\vec{v} =\lambda\vec{v}+\mu\vec{v}\\
C)&\quad 1*\vec{v}=\vec{v}\\
\end{align*}
$$

### Vektor typen

#### Einheitsverktor

Ein vector mit der länge 1

$$
\begin{align*}
\vec{a}^0&=\frac{1}{|\vec{a}|}*\vec{a}\\
&=\frac{1}{5}*\begin{pmatrix*}3\\-4\end{pmatrix*} \\
&=\begin{pmatrix*}
  \frac{3}{5}\\
  \frac{4}{5}
\end{pmatrix*}
\end{align*}
$$

#### Gegensvektor

Gleicher vektor aber in die entgegen gesetzte richtung

$$
\vec{a}\rightarrow-\vec{a}
$$

#### Ortsvektor

Beginnt immer am koordinaten ursprung und hat ein ende an einem punkt

#### Skalar

eine Relelle zahl

### Kollineare und Komplanare Vektoren

Wenn etwas kollinear oder komplanar ist bedeutet das es auch Linear abhänig wen es nicht das 

#### Kollinear

Ein vektor ist kolinear zu einem Vektor wenn er zu diesem auf irgendwie parallel zueinander sind,  die richtung in die sie verlaufen spielt keine rolle

wenn ein vektor parallel zu einem andern ist ist er durch ein vielfaches des anderen vektores darstellbar so kann man feststellen ob diesen linear abhänigsind oder nicht

$$
\vec{b}=k*\vec{a}\\
\begin{pmatrix*}2\\1\end{pmatrix*}=k*\begin{pmatrix*}4\\2\end{pmatrix*} \\\
\\
\begin{align*}
I_x:&2=k*4 \implies &k_1=\frac{1}{2}\\
II_y:&1=k*2 \implies& k_2=\frac{1}{2}\\
\end{align*}
\\
k_1=k_2\\
\implies \text{linear Abhänig}
$$

---

$$
\vec{c}=k*\vec{a}\\
\begin{pmatrix*}4\\4\end{pmatrix*}=k*\begin{pmatrix*}4\\2\end{pmatrix*} \\\
\\
\begin{align*}
I_x:&4=k*4 \implies &k_1=1\\
II_y:&4=k*2 \implies& k_2=2\\
\end{align*}
\\
k_1 \neq k_2\\
\implies \text{linear unabhänig}
$$

$$
\vec{a}\parallel\vec{b}\\
\vec{a}\nparallel\vec{c}
$$
#### Komplanar

erst in drei deminsionalen raum relevant

Ein vektor ist Komplanar zu einem anderen vektor wenn die vektoren zusamen eine ebene aufspannen sie müssen dafür nicht umbedinkt parallel sein oder in die gleiche richtung verlaufen

$$
\vec{c}=r*\vec{a}+s*\vec{b}\\
\vec{a}=\begin{pmatrix*}2\\3\\4\end{pmatrix*};
\vec{b}=\begin{pmatrix*}4\\5\\6\end{pmatrix*};
\vec{c}=\begin{pmatrix*}1\\5\\3\end{pmatrix*}
$$

$$
\begin{align*}
I_x:&1 =2r+4s \\
II_y:& 2=3r+5s\\
III_z:& 3=4r+6s\\
\end{align*}
$$

$$
\begin{align*}
&I_x :&  1 &=2r+4s & |&-4s\\
& & 1-4s&=2r & |& :2 \\
&I_x':&\frac{1}{2}-2s&=r&&&
\end{align*}
$$

$$
\begin{align*}
&r \text{ in } II :& 2  &=3(\frac{	1}{2}-2s)+5s & & \\
& & 2  &=\frac{3}{2}-6s+5s & |&-\frac{3}{2} \\
& & \frac{1}{2}  &=-s & |&*(-1) \\
& &  s &=-\frac{1}{2} & & \\
%& &   &= & |& \\
\end{align*}
$$

$$
\begin{align*}
&s \text{ in } I_x': & \frac{1}{2}-2*(-\frac{1}{2})  &=r & & \\
& & \frac{3}{2}  &=t & & \\
%& &   &= & |& \\
\end{align*}
$$

probe

$$
3=4*\frac{3}{2} +6*(-\frac{1}{2})\\
3=3 \\
\implies \text{ Die Vektoren sind Linear abhänig}
$$

### Basisverktoren

$$
\vec{e_1}=\begin{pmatrix*}1\\0\\0\end{pmatrix*};
\vec{e_2}=\begin{pmatrix*}0\\1\\0\end{pmatrix*};
\vec{e_3}=\begin{pmatrix*}0\\0\\1\end{pmatrix*};
$$

Aus diesen kann man jeden vektor bilden

$$
\vec{a} =
x*\begin{pmatrix*}1\\0\\0\end{pmatrix*}+
y*\begin{pmatrix*}0\\1\\0\end{pmatrix*}+
z*\begin{pmatrix*}0\\0\\1\end{pmatrix*}
$$

### Skalar produkt
 
immer eine zahl

$$
\vec{a}\circ\vec{b} \quad \LARGE \rightarrow \normalsize \quad a_x*b_x+a_y*b_y \\
\vec{a}\circ\vec{b} \quad \LARGE \rightarrow \normalsize \quad a_x*b_x+a_y*b_y+a_z*b_z
$$

$$
\cos \varphi = \frac{\vec{a}\circ\vec{b}}{|\vec{a}|*|\vec{b}|}
$$

Bei
nötig da eine betrag nie negativ sein kann oder auch ein Volumen bei der spat Berechnung
$$
|\vec{a} \circ \vec{b}| \\
|\text{skalar}| \\
\text{skalar} * \text{skalar}
$$

### Kreuzprodukt

Nur in $\mathbb{R}^3$
Ergebnis Vektor steht Ortogonal(senkrech) auf $\vec{a}$ und $\vec{b}$

$$
\vec{c}=\vec{a} \times \vec{b}
$$

#### rechte hand regel

richting nach rechter hand regel

Pistolen hand und mittel finger 90° zur handfläche

bsp.:
daumen ist ist richtung von $\vec{a}$
zeigefinger ist ist richtung von $\vec{b}$
mittelfinger ist ist richtung von $\vec{c}$

#### betrag

betrag von $\vec{a}\times\vec{b}$ ist die fläche des parallelograms zwischen $\vec{a}$ und $\vec{b}$

$$
A= |\vec{a}\times\vec{b}| = |\vec{a}|*|\vec{b}|*\sin(\alpha)
$$

#### Rechenregeln

$$
\begin{align*}
\vec{a}\times\vec{b} &= -(\vec{a}\times\vec{b}) \\
\lambda(\vec{a}\times\vec{b}) &= (\lambda\vec{a})\times \vec{b} = \vec{a} \times (\lambda\vec{b}) \\ 
(\vec{a}\times\vec{b})\times\vec{c}  &= \vec{a}\times\vec{b}+\vec{b}\times\vec{c}\\
\vec{a}\times\vec{b} &=  \vec{0} \to \text{Prüfung auf lineare abhänigkeit}
\end{align*} \\
$$

#### rechnen

$$
\vec{a_1}=\begin{pmatrix*}a_1\\a_2\\a_3\end{pmatrix*};
\vec{b_2}=\begin{pmatrix*}b_1\\b_2\\b_3\end{pmatrix*}; \vec{a},\vec{b}\in \mathbb{R}^3
$$

1. Es werden die beiden Vektoren jeweils nochmal unter sich selbst Geschieben
2. Oberste und unterste wegstreichen
3. die blaunen vektoren mit dem gegenüberliegenden aber eins weiterunterliegenenn kreuzen
4. die letzten (grün) werden nicht mehr gekreuzt

$$
\vec{a}\times\vec{b}=
\begin{pmatrix*}a_1\\a_2\\a_3\end{pmatrix*}\times\begin{pmatrix*}b_1\\b_2\\b_3\end{pmatrix*} =
\begin{align*}
&\begin{pmatrix*}\sout{a_1}\\ \textcolor{blue}{a_2}\\ \textcolor{blue}{a_3}\end{pmatrix*}\begin{pmatrix*}{\sout{b_1}}\\\textcolor{blue}b{_2}\\\textcolor{blue}{b_3}\end{pmatrix*}\\
&\begin{pmatrix*}\textcolor{blue}{a_1}\\\textcolor{green}{a_2}\\\sout{a_3}\end{pmatrix*}\begin{pmatrix*} \textcolor{blue}{b_1}\\ \textcolor{green}{b_2}\\\sout{b_3}\end{pmatrix*}
\end{align*}=
\begin{align*}
&\begin{pmatrix*}\sout{a_1}\\ \textcolor{blue}{a_2}\searrow b_3\\ \textcolor{blue}{a_3}\searrow b_1\end{pmatrix*}\begin{pmatrix*}{\sout{b_1}}\\ a_1\swarrow \textcolor{blue}b{_2}\\ a_2\swarrow \textcolor{blue}{b_3}\end{pmatrix*}\\
&\begin{pmatrix*}\textcolor{blue}{a_1}\searrow b_2\\\textcolor{green}{a_2}\\\sout{a_3}\end{pmatrix*}\begin{pmatrix*} a_2\swarrow \textcolor{blue}{b_1}\\ \textcolor{green}{b_2}\\\sout{b_3}\end{pmatrix*}
\end{align*}
= \begin{pmatrix*}a_2*b_3-b_2*a_1\\a_3*b_1-b_3*a_2\\a_1*b_3-b_1*a_2\end{pmatrix*} = \begin{pmatrix*}c_1\\c_2\\c_3\end{pmatrix*}
$$

#### Fläche
##### Fläche Parallelogramm

$$
A_\# = |\vec{a}\times\vec{b}|
$$

##### Fläche Dreiceck

$$
A_\triangle = \frac{1}{2} *|\vec{a}\times\vec{b}|
$$

#### Vloumen

##### Spat

$$
V_{spat} = |(\vec{a}\times\vec{b})\circ\vec{c}|
$$

Wenn =0 sind die Vektoren linear abhängig

##### Prisma

$$
V = \frac{1}{2}|(\vec{a}\times\vec{b})\circ\vec{c}|
$$

##### 4-Seitige Pyramide

$$
V = \frac{1}{3}|(\vec{a}\times\vec{b})\circ\vec{c}|
$$

##### Tetraeder 3-Seitige Pyramide

$$
V = \frac{1}{6}|(\vec{a}\times\vec{b})\circ\vec{c}|
$$

## Geraden

Standart Darstellung 
$$
\vec{x}=\vec{p}+\lambda*\vec{u} \\
$$

gerade wird durch 2 punkte festgelegt
### Aufstellen
$$
P=(1,2,3) \\
Q=(3,2,1) \\\
\\
\vec{x}=\vec{p}+\lambda*\vec{u} \\\
\\
\vec{p}=\begin{pmatrix*}P_x\\ P_y\\ P_z\end{pmatrix*}-\begin{pmatrix*}0\\0\\0\end{pmatrix*} =\begin{pmatrix*}1\\ 2\\3\end{pmatrix*}\\
\vec{u} = \begin{pmatrix*}Q_x\\ Q_y\\ Q_z\end{pmatrix*}-\begin{pmatrix*}P_x\\ P_y\\ P_z\end{pmatrix*}=\begin{pmatrix*}2\\ 0\\-2\end{pmatrix*} \\
\vec{x}=\begin{pmatrix*}1\\ 2\\ 3\end{pmatrix*}+\lambda*\begin{pmatrix*}2\\ 0\\ -2\end{pmatrix*} \\
$$

### prüfen ob ein punkt auf der geraden liegt

Der punkt wird als x eingesetzt und nur wenn alle drei Ergebnisse gleich sind ist der punkt auf der grade

$$
\vec{a}=\begin{pmatrix*}
  0\\-1\\10
\end{pmatrix*}; \qquad \vec{x}=\begin{pmatrix*}3\\2\\1\end{pmatrix*}+s*\begin{pmatrix*}-1\\-1\\3\end{pmatrix*}
$$

$$
\begin{rcases}
  0&=3-5 &\implies s=3\\
  -1&=2-5 &\implies s=3 \\
  10 &=1+3s &\implies s=3
\end{rcases}
= \qquad;A\in g
$$

### Durch stoß punkt

in der regel auf einer koordinaten eben

$$
\begin{rcases}
  S(s_1|s_2|s_3)\\
  x_1; x_2 : s_3 =0
\end{rcases}
\implies \vec{s}=\begin{pmatrix*}s_1\\s_2\\0\end{pmatrix*}
\qquad s_1,s_2 \in \mathbb{R}
$$

$$
\begin{pmatrix*}s_1\\s_2\\0\end{pmatrix*}=\begin{pmatrix*}2\\-1\\2\end{pmatrix*}+t*\begin{pmatrix*}-2\\6\\4\end{pmatrix*} \begin{matrix*}
  \\
  \\
  \implies III: 0=2+4t \implies t=-0,5
\end{matrix*}
$$
$$
t \text{ in } I : s_1 = 2-0,5-(-2) \implies s_1=3\\
t \text{ in } II : s_2 = -1+6*(-0,5) \implies s_2 = -4 \\
\implies S(3|-4|0)
$$

<!-- ### mit Varable -->

### Koordinaten gleichung

auch Paramterfreie darstellung

$$
x_2 =mx_1+t
$$

## Parameter From

$$
\vec{x}=\begin{pmatrix*}x_1\\x_2\end{pmatrix*}=\begin{pmatrix*}a_1\\a_2\end{pmatrix*}+\lambda*\begin{pmatrix*}1\\ m\end{pmatrix*}; \qquad\lambda\in\mathbb{R} \\\
oder\\
\vec{x}=\begin{pmatrix*}x\\ y\end{pmatrix*}=\begin{pmatrix*}x\\ mx+t\end{pmatrix*}+\lambda*\begin{pmatrix*}0\\ t\end{pmatrix*}; \qquad x\in\mathbb{R}
$$

### Normalen Form

$$
\vec{n}\circ\vec{x}=\vec{n}\circ\vec{a} \Leftrightarrow \vec{n}\circ (\vec{x}-\vec{a})=0
$$

$\vec{n}$ erhält man indem zwei koordinaten von $\vec{u}$ miteindander vertauscht werden und eine koordinaten von den getaischenten mit -1 multipliziert

Am besten immer daruf schauen das man alles postiv hat

$$
\mathbb{R}^2: \vec{u}=\begin{pmatrix*} u_1\\u_2\end{pmatrix*} \implies\vec{n}=\begin{pmatrix*} u_2\\-u_1\end{pmatrix*}
$$

in $\mathbb{R}^3$ wird noch eine variable gleich null gesetzt

$$
\vec{u}=\begin{pmatrix*} u_1\\u_2\\u_3\end{pmatrix*} \implies \vec{n}=\begin{pmatrix*} 0\\-u_3\\u_2 \end{pmatrix*} \text{Auch anderst möglich z.b. } \begin{pmatrix*} u_2\\-u_1\\0\end{pmatrix*}
$$

### Umrechnung $\mathbb{R}^2$


#### Parameterform in Normalenform

$$
g: \vec{x}=\begin{pmatrix*}2\\-1\end{pmatrix*}+\lambda*\begin{pmatrix*}-2\\4\end{pmatrix*}, \qquad \lambda \in \mathbb{R}\\
\text{Tausch von u durchführen }\\
\implies \vec{n}=\begin{pmatrix*}4\\2\end{pmatrix*}
$$

$$
\begin{pmatrix*}4\\2\end{pmatrix*} \circ (\vec{x}-\begin{pmatrix*}2\\-1\end{pmatrix*})=0 \\
\text{Klammer auflösen}\\
\begin{pmatrix*}4\\2\end{pmatrix*}\circ \vec{x}-\begin{pmatrix*}4\\2\end{pmatrix*}\circ\begin{pmatrix*}2\\-1\end{pmatrix*} =0\\
\text{Vektorprodukt auflösen}\\
\begin{pmatrix*}4\\2\end{pmatrix*}\circ \begin{pmatrix*}x_1\\ x_2\end{pmatrix*} -6 =0
$$

#### Normalenform in koordinatenform

$$
\begin{align*}
g: \begin{pmatrix*}4\\2\end{pmatrix*}\circ \begin{pmatrix*}x_1\\ x_2\end{pmatrix*} -6 &=0\\
\text{Funktionen auf stellen durch}& \text{ ausschreiben des Vektorprodukts}\\
4x_1+2x_2-6 &=0 \\
\text{ mit } x_1=x &\text{ und } x_2 =y\\
4x+2y-6 &=0\\
\implies g : y&=-2x+3
\end{align*}
$$

#### koordinatenform in normalenform

Vektor produkt zurück schreiben

$$
\begin{align*}
 \textcolor{orange}{4}x+ \textcolor{orange}{2}y-6&=0\\
\text{ mit } x_1=x &\text{ und } x_2 =y\\
 \implies \begin{pmatrix*} \textcolor{orange}{4}\\ \textcolor{orange}{2}\end{pmatrix*}\circ \begin{pmatrix*}x_1\\ x_2\end{pmatrix*} -6 &=0
\end{align*}
$$

#### Normalenform in Paramterform

Komplexeste

Aufpunkt ermitteln :

$$
\underbrace{\begin{pmatrix*}4\\2\end{pmatrix*}\circ\begin{pmatrix*}x_1\\x_2\end{pmatrix*}}_{\vec{n}\circ\vec{x}}-\underbrace{6}_{\vec{n}\circ\vec{a}}=0 \\
\implies \vec{n}  \circ \vec{a}=6 \\
\implies \begin{pmatrix*}4\\2\end{pmatrix*} \circ \begin{pmatrix*}a_1\\a_2\end{pmatrix*} =6\\
\text{eine Stelle Kann frei gewählt werden}\\
a_1 = 2\\
\implies 4*2+2a_2 =6 \\
a_2 =-1\\
\vec{a}=\begin{pmatrix*}2\\-1\end{pmatrix*}
$$

Richtingsvektor ermitteln:

$$
\vec{u} \perp\vec{n}; \qquad \vec{n}=\begin{pmatrix*}4\\2\end{pmatrix*} \quad \implies \vec{u}\circ\vec{n} =0 \\
\text{Tausch trick verwenden} \\
\vec{u}=\begin{pmatrix*}-2\\4\end{pmatrix*}\\
\implies g: \vec{x}=\begin{pmatrix*}2\\-2\end{pmatrix*}+\lambda*\begin{pmatrix*}-2\\4\end{pmatrix*} \qquad ;\lambda \in \mathbb{R}
$$

## Ebenen
