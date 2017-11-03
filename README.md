# Simple LaTeX Class for Scribe
This is a simple lecture LaTeX class for students to create lecture scribe. It is based on [the scribe of MIT 6.851](http://courses.csail.mit.edu/6.851/fall17/scribe/lec1.zip).


## Usage

The following gives you a simple example of how to use this latex class.

```TeX
\documentclass[11pt]{lecture}
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

After compiling, you will get [example.pdf](./example.pdf).


