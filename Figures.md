# One Figure


```
\begin{figure}[h!]
    \captionsetup{labelformat=empty, justification=centering}
    \centering
    \includegraphics[width=3in]{images/3}
    \caption{As both $a$ and $b$ increase, the precision increases too. \\ Therefore we get more concrete variance of Gaussian when we apply \textcolor{blue}{Bayes inference of the precision $\lambda$}}
    \label{e3}
\end{figure}

```

# SubFigures

```
\begin{figure}[h]
    \begin{subfigure}[t]{3in}
        \includegraphics[width=3in]{images/1}
        \caption{
        \textbf{Varying the polynomial term} \\ Since the almost half of the probability lie in $(0,1)$, \\
        increasing \hl{$\*a$ makes the distribution flatten.}\\(consider the polynomial in $(0,1)$
        }
        \label{e1}
    \end{subfigure}
    \begin{subfigure}[t]{3in}
        \includegraphics[width=3in]{images/2}
        \caption{\textbf{Varying the exponential term} \\ As expected, \hl{increasing the $b$ term \\makes exponential more sharp,}\\
        and therefore the distribution becomes sharp too. }
        \label{e2}
    \end{subfigure}
\end{figure}

```
