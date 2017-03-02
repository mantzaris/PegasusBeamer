# PegasusBeamer
## A beamer theme for the University Of Central Florida (UCF)

1. You must download the .sty file and the *stylefiles* folder into the directory where you have your .tex latex/beamer file

2. At the start of the file, after defining the document class at the top: **\documentclass{beamer}**, put the line **\usetheme{PegasusUCF}**

3. Fill in the title and short title  by changing the text in the square and curly brackets for the *\title* tag: **\title[short talk title]{title of talk}**

4. Fill in the author name from the *\author* tag: \author{Author name}

5. If you would like the titleframe to have the general UCF logo for the university leave the line **\newcommand{\deptname}{0}** uncommented.

6. If you would like to have on the title frame the logo of your department leave the line of your department uncommented (no % at start) and the rest commented (with % at start). Eg. **\newcommand{\deptname}{1}%STATISTICS** for the statistics department. 

7. *example.tex* gives a working template and *example.pdf* shows the output pdf


```latex
\documentclass{beamer}
\usetheme{PegasusUCF}

%-------------------------------
\title[GoKnights]{UCF Lecture 8}
\author{Alexander V. Mantzaris}
%>>>>UNCOMMENT 1 FOR YOUR DEPTARTMENT
\newcommand{\deptname}{0}
%\newcommand{\deptname}{1}%STATISTICS
%\newcommand{\deptname}{2}%MATHEMATICS
%\newcommand{\deptname}{3}%ENGINEERING AND COMPUTER SCIENCE
%\newcommand{\deptname}{4}%ELECTRICAL ENGINEERING AND COMPUTER ENGINEERING
%\newcommand{\deptname}{5}%IST INSTITUTE FOR SIMULATION AND TRAINING
%\newcommand{\deptname}{6}%PHYSICS
%\newcommand{\deptname}{7}%MECHANICAL AND AEROSPACE ENGINEERING
%\newcommand{\deptname}{8}%COMPLEX ADAPTIVE SYSTEMS LABORATORY
%\newcommand{\deptname}{9}%CENTER FOR ADVANCED TRANSPORTATION SYSTEMS SIMULATION
%\newcommand{\deptname}{10}%CHEMISTRY
%\newcommand{\deptname}{11}%BIOLOGY
%\newcommand{\deptname}{12}%ECONOMICS
%\newcommand{\deptname}{13}%SOCIOLOGY
%\newcommand{\deptname}{14}%PSYCHOLOGY
%\newcommand{\deptname}{15}%BUSINESS AND ADMINISTRATION
%\newcommand{\deptname}{16}%COLLEGE OF SCIENCES

%<<<<<
\date{\vspace{-8cm}}

%--------------------------------



%%%%%%%%%%%%%%%%
\begin{document}
```
