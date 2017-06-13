
# Geany Editor Syntax Highlighting


## Purpose

My slightly eccentric, but personally essential, Geany colour schemes for a black editor background.


## Colours

Colours are inverted HTML codes, to conform with the 'inverted' editor background.


## Geany Version

Version 1.27 on Linux.


## Global Template Files

*/usr/share/geany/filetypes.x*


## Local File Destination

*~/.config/geany/filedefs/*


## Usage

Copy the repo files to *~/.config/geany/filedefs/*

----

#### Colour Usage in Future Geany Versions

Copy the template filetypes files from:

*/usr/share/geany/*

to:

*~/.config/geany/filedefs/*


In each *~/.config/geany/filedefs/* file, copy and paste the `[styling=HTML]` section and colour codes from the additions directory.

Change the colour code values to your preference.  The *gpick* application in the Ubuntu repo has a decent colour code inverter (*Scheme generation*).

(Ignore the `[styling]` section if already present in the file.)

Geany should pick up the changes immediately on file save. If not:

*Tools > Reload Configuration*

If duplicate definitions occur later in the same file, comment out or delete (else they will override earlier definitions).
