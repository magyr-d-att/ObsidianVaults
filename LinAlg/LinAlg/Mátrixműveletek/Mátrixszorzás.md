---
tags:
  - linalg
  - mátrix
  - alapművelet
---
$$ A \times B $$
Nem [[Kommutatív]], csak [[Asszociatív]] !!!!


Kizárólag akkor valid ha:
$$  (n \times k) \times (k \times m) = (n \times m) $$
pl:
$$
\begin{bmatrix}
3 & 4 \\
1 & 5
\end{bmatrix}
\times 
\begin{bmatrix}
2 & 4 & 7 \\
1 & 5 & 3
\end{bmatrix}
=
\text{Res}
$$

![[Mátrixszorzás Menete]]
Első sor:
$$
r_{11} = (a_{11}\times b_{11}) + (a_{12}\times b_{21}) = 3 \times 2 + 4 \times 1 = 10
$$
$$
r_{12} = (a_{11}\times b_{21}) + (a_{12}\times b_{22}) = 3 \times 4 + 4 \times 5 = 32
$$
$$
r_{13} = (a_{11}\times b_{31}) + (a_{12}\times b_{32}) = 3 \times 7 + 4 \times 3 = 33
$$

Második sor:
$$
r_{21} = (a_{21}\times b_{11}) + (a_{22}\times b_{21}) = 1 \times 2 + 5 \times 1 = 7
$$
$$
r_{22} = (a_{21}\times b_{21}) + (a_{22}\times b_{22}) = 1 \times 4 + 5 \times 5 = 29
$$
$$
r_{23} = (a_{21}\times b_{31}) + (a_{22}\times b_{32}) = 1 \times 7 + 5 \times 3 = 22
$$

$$
\text{Res = }
\begin{bmatrix}
10  &  32  & 33 \\
7 & 29 & 22
\end{bmatrix}
$$


