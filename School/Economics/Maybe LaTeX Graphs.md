```tikz
\usepackage{pgfplots}
\pgfplotset{width=10cm,height=10cm}

\begin{document}
  \begin{tikzpicture}
    \begin{axis}[xmin=-2,xmax=2,ymin=-2,ymax=2]
	\addplot[no marks,samples=100]({cos(deg(x))},{sin(deg(x))});
    \end{axis}
  \end{tikzpicture}
\end{document}
```
