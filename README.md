# LaTeX Code Generator

## Description
This is a (presumably GUI) application for generating tables, structograms and other elements in LaTeX code. There will be a GUI Version in Lazarus/Free Pascal and a command line tool written in Python.

## Support
The following elements will be supported:
* structograms (StrukTeX)
* tables (default LaTeX)

In later versions:
* ER-models
* relational database models

## Requirements
* TeXlive
* StrukTeX

* command line tool
** python 2.7

## Usage
### GUI
not yet implemented

### Command Line Tool
Either feed it a file:
./texparser <file>
or pipe into in teh pipe:
cat file | texparser
