Modularity demo
===

This demonstration illustrates the `\subimportlevel` macro.
This macro allows us to import documents in a way such that the depth of the sections/subsections/etc automatically adjusts to the point in which that document was imported.
To see the macro work, follow these steps:

1. Build `octopuses/octopuses.tex` and view the output.
You will see a perfectly reasonable, short article about octopuses, with two sections.

1. Build `main.tex` and view the output.
You will see that the article on octopuses has been included, and the section depth has been automagically updated.
This is not possible with the standard `\section`, `\subsection`, etc. commands which work with absolute depths.
Our ability to build `octopuses/octopuses.tex` by itself *or* include `octopuses/octopuses_content.tex` *and* get the headings right is the special feature we're demonstrating.

1. For fun, go into `animals_content.tex` and uncomment the two final lines, then rebuild `main.tex` to see an extended example with more sections.


