[![Build Status](https://travis-ci.com/rstudio/bookdown-demo.svg?branch=master)](https://travis-ci.com/rstudio/bookdown-demo)

**Solving Statistical Problems** is a bookdown project compiling techniques, intuition, and useful theorems for solving introductory graduate-level problems in probability and statistical inference. It is not meant to present topics from the ground-up; rather, it is meant as a supplement to improve problem-solving speed and skill. The authors are currently preparing this in preparation for the Harvard Biostatistics PhD first-year qualifying examination. 

Since this book is based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown), please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile this example into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

For contributors, note that...
- LaTeX packages can be added by including them in `preamble.tex`. 
- Theorems, definitions, etc. can be added as explained [here](https://bookdown.org/yihui/bookdown/markdown-extensions-by-bookdown.html)
