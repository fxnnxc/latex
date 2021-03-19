# latex

## Cases

```
\begin{cases}
    x(n), & \text{for } 0 \leq n \leq 1 \\
    x(n - 1), & \text{for } 0 \leq n \leq 1 \\
    x(n - 1), & \text{for } 0 \leq n \leq 1
  \end{cases}
```

## Line
```
\usepackage{ulem}
\sout{awefwef}
```
## TextBox 

```
\usepackage{tcolorbox}
\begin{tcolorbox}
~~~~
\end{tcolorbox}
```
Change color
```
\begin{tcolorbox}[colback=white!5!white,colframe=red!75!black]
```

## paper size

```
\usepackage{geometry}
\geometry{ a4paper, left=20mm, top=20mm}
```

## Short cut

```
\def\*#1{\mathbf{#1}}
\def\&#1{\bm{#1}}

\*x
```

## Theorem, Remark, Note

```
\newtheorem{theorem}{Theorem}
\newtheorem*{theorem*}{Theorem}
\newtheorem*{remark}{Remark}
\newtheorem*{note}{Note}
```

## Textcolor and Highlight

```
\usepackage{xcolor}
\usepackage{color,soul}

\textcolor{red}{teeee}
\hl{werwe}
```

## Code(python)
```
\usepackage{minted}
\begin{minted}{python}
import numpy as np
    
def incmatrix(genl1,genl2):
    m = len(genl1)
\end{minted}
```

## Horizontal line

```
\usepackage[ruled,vlined]{algorithm2e}

\vspace{5pt}
\hrule 
```
