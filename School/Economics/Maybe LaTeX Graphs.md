```tikz
\usepackage{pgfplots}
\usepackage{xcolor}
\usetikzlibrary{backgrounds}

\begin{document}
  \begin{tikzpicture}[background rectangle/.style={fill=blue}, show background rectangle]
    \begin{axis}
	\addplot[no marks]{x^2};
    \end{axis}
  \end{tikzpicture}
\end{document}
```
