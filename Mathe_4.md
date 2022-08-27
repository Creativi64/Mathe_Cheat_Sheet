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

#### Rechengesetze

#### Skalar multiplkation
### Vektor typen

#### Einheitsverktor

#### Gegensvektor

#### Ortsvektor

#### Skalar