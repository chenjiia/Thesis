Look through each .tex file for explanation of what to fill in each.

After you have edited all of the .tex files, here's how you compile the .pdf:
 1) run latex or pdftex on ThesisMaster.tex (it will call on the other .tex files automatically)
 2) run bibtex on your .bib file
 3) run latex or pdftex on ThesisMaster.tex again (perhaps several times until number of warnings stops changing)

A WinShell project file is included (if you choose to use WinShell for editing) which will allow you to hit the compile button while any tex file is open, and the master will be called.

Credits: (all from the Dept. of Physics and Astronomy)
Hakim Meskine for providing the original framework
Michael Mayo and Matt Mower for subsequent updates