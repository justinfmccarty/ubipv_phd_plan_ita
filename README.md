# Latex_Templates

Contains templates for Master Thesis Reports and PhD Proposals.

Please feel free fix any issues you find and commit new versions. If you are unfamilar with github, then check out http://rogerdudler.github.io/git-guide/

##Trouble Shooting
If you are having issues and google can't help you then contact PJ

#Master Thesis Layout

##Preamble
The preamble contains all the plugins required to run the document

##Thesis.tex
The `Thesis.tex` is the root file which compiles the document. It will call the `preamble` and the various chapters that are nested in seperate folders

##Images Folder
All images/figure are to be stored here. The `preamble` has set a graphics path directly to this folder

##00_Front
The front matter (everything that comes before the Introduction) is stored in the 00_Front folder. 

###Title Page
Fill in your name, title, and supervisors here

###Abstract
Write this last

###Acronyms
The acronyms are manually listed in a seperate table file `acronyms.tex`. This will need to be manually edited

###List of Figures and Tables
Will automatically compile
