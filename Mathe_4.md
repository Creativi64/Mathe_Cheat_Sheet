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
    - [Skalar produkt](#skalar-produkt)

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

### Skalar produkt

