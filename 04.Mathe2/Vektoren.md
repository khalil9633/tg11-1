# Vector
Um einen Vector darzustellen, wird die **array**-Umgebung verwendet. Da hier nur eine Spalte dargestellt wird, gibt es nur einmal {r} für rechtsbündige Formatierung. Gültige Formtierungen sind l, r oder c für linksbündig, rechtsbündig oder zentriert.

## Einfaches Beispiel:
Array mit 2 Spalten, wobei die erste Spalte rechtsbündig und die zweite Spalte linksbündig ist.

$
\begin{array}{rr}
 a  & d_1\\ 
 -b & e  \\ 
 c  & f 
\end{array}
$

wird dargestellt mit:

```markdown
>$
\begin{array}{rl}  
      a  &  d_1\\
     -b  &  e  \\
      c  &  f 
\end{array}
$
```


## Beispiel Vector:
$
\vec{x}= 
\left( 
   \begin{array}{r}
     1\\
     -2\\
      3\\ 
    \end{array} 
\right) +t \cdot 
\left( 
   \begin{array}{r}
      3\\ 
      6\\
      1 
   \end{array} 
\right)
$

