!! Thesis report made in LaTex

To compile the LaTex files you will need a Tex package.
I recomend TexLive, it's usually included in the repositories of most GNU/Linux
distributions.
Either you use the Makefile that I removed in a previous commit, or use the
latexmk command. Just run this command once in the root of the thesis, all files
will be compiled as needed in two PDF files. One for the thesis, another one
for the presentation.

Be aware that compiling with pdflatex or latex commands requires you to run them
multiple times, and also to generate the bibliography manually. Just use
latexmk, as it takes care of all the details.
