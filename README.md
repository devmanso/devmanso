\documentclass{article}
\usepackage{xcolor}         % For text color
\usepackage{graphicx}       % For including images
\usepackage{tikz}           % For advanced positioning

\begin{document}

\begin{tikzpicture}[remember picture, overlay]
    \node[anchor=north west, inner sep=0] at (current page.north west) {
        \includegraphics[width=\paperwidth,height=\paperheight]{https://raw.githubusercontent.com/devmanso/devmanso/test/fumodance-cirno.gif}
    };
    \node[anchor=north west, inner sep=10pt] at (current page.north west) {
        \textcolor{red}{\Huge This is a test text overlaid on the background image.}
    };
\end{tikzpicture}

\end{document}
