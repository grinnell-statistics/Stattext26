---
title: "Tcolorbox Test"
output:
  html_document:
    df_print: paged
  bookdown::pdf_book:
    latex_engine: xelatex
    keep_tex: true
header-includes:
- \usepackage{tcolorbox}
- \newtcolorbox{blackbox}{colback=gray!10, colframe=blue, coltext=black, boxsep=5pt,
  arc=4pt, title=MATHEMATICAL NOTE}
---



# Chapter 1

\begin{blackbox}
For any population with mean $m$ and finite standard deviation $s$, the central limit theorem states that  
the sample mean $\bar{x}$ from an independent and identically distributed sample tends to follow the normal  
distribution if the sample size is large enough. The mean of $\bar{x}$ is the same as the population mean $m$, while  
the standard deviation of $\bar{x}$ is $\frac{s}{\sqrt{n}}$, where $n$ is the sample size.
\end{blackbox}
