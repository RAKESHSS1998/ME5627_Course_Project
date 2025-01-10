A Classic Thesis Style v4.6
An Homage to The Elements of Typographic Style
Copyright (C) 2018 André Miede and Ivo Pletikosić 

Customized for IIT Palakkad by Jasine Babu and Sravan Kumar Perumalla 
(jasine@iitpkd.ac.in, sravanperumalla@gmail.com) 
For reporting issues, IIT Palakkad users may contact jasine@iitpkd.ac.in
Last Updated on Nov 4, 2024.  

Software Requirements : texlive-full, pdflatex, latexmk, biblatex

Compilation Steps :
1. latexmk -C
2. rm *.bbl *.loa *.lol *.nlo *.nls *.xml *.aux
3. latexmk -f -pdf classicthesis.tex
4. makeindex classicthesis.nlo -s nomencl.ist -o classicthesis.nls
5. pdflatex classicthesis.tex
6. latexmk -c

Important Notes :
1. The file classicthesis.sty should not be edited.
2. For editing other files, carefully follow the instructions mentioned in the file itself in the form of comments. Whenever it is mentioned "Do not edit" in any file, follow the instruction.
3. Information such as your name and title of your thesis are to be set by editing the file classicthesis-config.tex. Two important options are the flags 'eulermath' and 'printready' that configurable in the file classicthesis-config.tex. For draft submission along with synopsis, enable watermark by setting 'drafting' to true in the file classicthesis-config.tex  
4. Please see the file ClassicThesis.pdf for more information.

License:
This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

Your comments are highly appreciated.
