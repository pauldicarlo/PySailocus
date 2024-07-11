PySailocus
==================

Python, Tkinter, & Forces on a Sail....

![picture](https://raw.githubusercontent.com/sailocus/PySailocus/master/src/pysailocus/resources/images/PySailocus.png)   

---
> "The approximate locus of net aerodynamic force on a craft with a single sail is the centre of effort (CE ) at the geometric centre of the sail".
>     https://en.wikipedia.org/wiki/Forces_on_sails



## Background
Sailocus is an attempt to write code that will explore the aerodynamic forces on sails.  It is meant to be a development exercise to build my proficiency in some new programming languages... as well as better understand forces on sails... and maybe even design my own sails someday.

## Known Problems
This is very rough code and I haven't touched it in years so it needs some TLC.  Not sure if there my code has problems with the current version of [TKinter](https://docs.python.org/3/library/tkinter.html) (Python UI library)
* Running in VSCode debugger does not seem to work -- looking at it 20240711
* Clicking on edit boxes does not always work, and you have to select the existing contents, then tab from UI element to the next to finally to the **Calculate** button and press the space bar. -- looking at it 20240711

## Running / Debugging
### Setup Env
1. Open a terminal 
1. cd to root directory of project
1. Do only once:
   1. python3 -m venv venv
   1. source venv/bin/activate
   1. pip3 install tk

### To Run From Command Line
1. Open a terminal 
1. cd to root directory of project
1. source venv/bin/activate
1. python3 src/PySailocus_app.py

### VScode Setup For Debugging
I'm having a problem getting code to work in a debugger, so for now best to run from command line.
1. Open PySailocus project dir in VSCode, note there is a .vscode launch configuration in repo
1. Open a VSCode terminal 
   1. source venv/bin/activate
1. Run->Debug from menu at top of VSCode

#### The Name Sailocus
The name Sailocus comes from "sail" and "locus" (see quote above).

## About
PySailocus is a project for Python/Tkinter development.  Tkinter was chosen because it usually comes already with Python.  The application is a currently a PROTOTYPE right now, where it will calculate the center of effort for a single sail (being 3 or 4 sided).  As time progresses (and my knowledge of sails) the application will be flushed out to make it more robust.  

### Caveat
You should only use sails designed and made by a professional.  This code is just for a learning excercise.  

## More Info
See [PySailocus Project](https://github.com/pauldicarlo/PySailocus) for more information.


