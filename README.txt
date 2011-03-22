README file for DIT Final-Year Project LaTeX template.

In this archive you'll find all of the files you need to get started using LaTeX to typeset your final-year project report. 

Using LaTeX will render a much more visually appealing result than using a Word processor. You do, however, have to learn the rudiments 
of LaTeX to get the best out of it - just like any software system. 

Getting started
* http://en.wikibooks.org/wiki/LaTeX/ - this is an excellent resource and will teach you pretty much everything you need to know.
* http://www.latex-project.org/ - this is the LaTeX project site and has more information of interest. Pay particular attention to the 
"Getting LaTeX" page.
* There are lots of GUI front-end programs to help you with the mechanics of creating LaTeX files. As I use Linux, I favour
Texmaker (http://www.xm1math.net/texmaker/) but there are lots of others for all OS platforms. PCTeX (http://www.pctex.com/) 
is probably a good option for MS Windows.

Things to watch
* Start by looking at the ProjectMain.tex file. This is the document that "includes" all others. A bit like the "main" function 
of a program really. The trick is to create a separate .tex for each chapter of your document.
* Reference information is created using an add-on called BibTeX. When you compile your document, run this separately. It will 
be accessible from the toolbar of your GUI app.
* Code listings are laid out using a "listings" environment - see example "\lstinputlisting" command in "Appendix1.tex". if you tell
it the language of the code you'll get nicely formatted listings .
* Learn how to include (and standardise) images, tables etc. Pay attention to the use of captions.
* Also learn how to cite references (see examples in "Introduction.tex".

Good luck and have fun!

Mark Foley.
November 2010.

