# HiLaTeX

## Description
This repository is dedicated to the mutal support of LaTeX and hitex.

## Installation
hitex became a part of the TeX Live distribution in 2022.  The initial
distribution did provide the hilatex executable as a link to the hitex
executable as usual, but the generation of the hilatex format file was
still disabled because there were some LaTeX requirement not yet met
by the hitex executable.

This resository is dedicated to resolving not only issues concerning
the basic requirements for running LaTeX using hilatex, but also
strives to support advanced features of LaTeX like the definition of
links and bookmarks or the embedding of graphics.
Therfore the following directories provide updated files that will 
ultimately be part of the TeX Live development sources and then
move to the TeX Live distribution. The HINT file viewers are an
exception: the production versions of the executables are distributed 
through the various App Stores or on the HintView home page:
http://hint.userweb.mwn.de/hint/hintview.html 

## Directories
base - for supplemental tex files. Stable versions should go to the TeX Live
distribution in directory texlive/20XX/texmf-dist/tex/hitex/base/

doc - for documentation

tests - for short tex and latex files used as test cases

format - for format files

bin - for binaries
     Especially if branches will require experimental extension of hitex
     and the hintview viewing applications, these directories will contain
     binaries with these extensions. To support experimenting without going
     through the process of compiling binaries.

bin/win32 - for WIN32 executables

bin/linux - for linux binaries

## Roadmap
The repository will target first the hyperref package of LaTeX with
the aim of supporting first internal links and later
bookmarks. Currently the HINT file format does not have support for
external links.


## Authors
Martin Ruckert, Hochschule M�nchen,

## WWW
http://hint.userweb.mwn.de/

## License
All the examples and code you find here is in the public domain unless stated otherwise.

## Project status
Initial setup.

