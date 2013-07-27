HHL-LaTeX-template
==================

A LaTeX template according to HHL's "Guidelines for writing  an academic assignment" from 11th of May 2011

Build the document using make or your favourite TeX editor.
I recommend http://texstudio.sourceforge.net/

The structure is as follows:

main.tex (1) - The main document, use it as master in you TeX editor

-   configuration.tex - The configuration of your document
-   package.tex (1) - The main packages required for the document
-   -   user.sty - Add the packages you need here
-   komaconfig.tex (1) - The KOMA script configuration
-   metadata.tex - The document meta data, add your name here
-   title.tex (1) - The title page
-   foreword.tex - Add your foreword here
-   content.tex - Tables of content, normally you don't need to change this file
-   document.tex - Filling this file is your task
-   bibliography.tex (1) - The bibliography
-   -   library.bib - Your BibTex library, generate it using Mendeley or any other tool
-   index.tex (1) - Generate an index, if required
-   authorship.tex - Put your signature here

(1) - Do not edit these files unless you know what you're doing.
The author will provide no support if these files have been changed.

You may use this template as is.
The author offers you no warranty.
Using the template is free - for private and educational use.
Change it, distribute it, but never remove the name of the author from any of the files.

Gerrit Beine <gerrit.beine@gmx.de>
2013/04/03