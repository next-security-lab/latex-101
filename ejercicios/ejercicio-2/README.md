# Segundo ejercicio

Crear el documento LaTeX a partir del pdf [Ejercicio-2.pdf](https://github.com/next-security-lab/latex-101/blob/master/ejercicios/ejercicio-2/Ejercicio-2.pdf).

**TAREA**: Añadir fórmulas matemáticas.

Aquí está el esqueleto del documento:

```latex
\documentclass{article}
\usepackage[utf8]{inputenc}
% Añadir paquete para fórmulas amsmath

\title{Taller \LaTeX{} -- Ejercicio 2}
\author{Tu nombre}
\date{26 de junio de 2019}

\begin{document}

\maketitle

\tableofcontents


\section{Introduction}
\lipsum[10]
\section{Parte 1}
\lipsum[1]
\subsection{Parte 1.1}
\lipsum[2]
\subsubsection{Parte 1.1.1}
\lipsum[3]

% Añadir en cada sección la fórmula correspondiente

\section{Fórmulas}
\subsection{Fórmula 1}

\subsection{Fórmula 2}

\subsection{Fórmula 3}

\end{document}
```
