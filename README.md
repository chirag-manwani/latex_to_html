# latex_to_html
Compiler for converting Latex documents to HTML documents using Flex, Bison and C++. 

The features(tags) of LaTeX considered:-
    
    \section
    \subsection
    \par
    \label
    \ref
    \textbf
    \textit
    \underline
    \enumerate
    \item
    tabular environment
    figure environment
    \includegraphics
    \caption
    Math mode with $...$
    \frac{numerator}{denominator}
    \sqrt
    $\sum... $
    $\int...   $

Flex used for Lexical Analysis.
Bison used for Syntax Analysis.
Grammar Actions and Main program written in C++.

To run code-
1. cd into directory using terminal
2. run- "make"
3. run ./compiler sample.tex
