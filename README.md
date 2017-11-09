# Simple LaTeX Class for Scribe
This is two simple lecture LaTeX classs for students to create lecture scribe and reports for assignments --- [scribe.cls](./scribe.cls) and [report.cls](./report.cls). They are based on [the scribe of MIT 6.851](http://courses.csail.mit.edu/6.851/fall17/scribe/lec1.zip).


## Usage

The following gives you a simple example of how to use `scribe.cls`, that is identical for `report.cls`.

```TeX
\documentclass[11pt]{scribe}
\usepackage{lipsum}
\begin{document}
\course{CS 6210/CS 4210 ADVANCED OPERATING SYSTEMS}
\title{Distributed Shared Memory (Part I)}
\semester{Fall 2017}
\instructor{Prof. Umakishore Ramachandran}
\author{Long Gong}
\maketitle

\section{Overview}
\lipsum
\end{document}
```

After compiling, you will get [scribe.pdf](./scribe.pdf).


