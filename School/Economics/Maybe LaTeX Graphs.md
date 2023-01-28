```tikz
\usepackage{pgfplots}
\pgfplotsset{width=10cm,height=10cm}

\begin{document}
  \begin{tikzpicture}
    \begin{axis}[axis x line=center,axis y line=center,xmin=0,xmax=1.5,ymin=0,ymax=1.5]
	\addplot[no marks,samples=500]({cos(deg(x))},{sin(deg(x))});
    \end{axis}
  \end{tikzpicture}
\end{document}
```
