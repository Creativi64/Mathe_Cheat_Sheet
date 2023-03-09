# Mathe 5


<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Mathe 5](#mathe-5)
  - [Gebrochen rationale Funktion](#gebrochen-rationale-funktion)
    - [Definitions Bereich](#definitions-bereich)
    - [Symmetrie](#symmetrie)
    - [Achsen schnittpunkte](#achsen-schnittpunkte)
      - [Y achse](#y-achse)
      - [X Achse](#x-achse)
    - [Extrempunkte](#extrempunkte)

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

#### X Achse

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
