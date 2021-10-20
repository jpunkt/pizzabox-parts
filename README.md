# pizzabox-parts

Interactive theatre performance in a pizza box. This repository contains all design files needed to reproduce the physical components.

## File Structure

        .
        ├── Design           [Editable 2D and 3D part design]
        │   ├── 2D-Printer
        │   ├── 3D-Printer
        │   └── Lasercutter
        ├── Production       [Files used for production]
        │   └── SIBI            [Sub-Folders per prototyping version]
        │       ...
        └── Archive          [Design files of previous prototyping versions]
                
## Style Guide

Files must only be added in the appropriate subdirectories. `Production` folder contains one subdirectory per prototyped version, for documentation processes. Design files are named to reflect the prototype version they are intended for as a prefix, i.e. all files related to *SIBI* begin with `sibi_`. Design files for old prototype versions may be moved to the `Archive`.

File names are lower case only, no white space characters.

## Ignored files

FreeCAD creates backup files with the file ending `FCStd1`. These are only useful in the case of a program crash, and have been added to the `.gitignore` file.
