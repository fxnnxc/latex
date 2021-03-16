# latex

## TextBox 

```
\usepackage{tcolorbox}
\begin{tcolorbox}
~~~~
\end{tcolorbox}

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

## Horizontal line

```
\usepackage[ruled,vlined]{algorithm2e}

\vspace{5pt}
\hrule 
```