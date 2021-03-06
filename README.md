A fork of glimmer 3.02b with improved file output parsability

Full instructions for installing and running Glimmer are in file
glim302notes.pdf in this directory.

Here's a quick start guide for the inpatient:

- To build all Glimmer programs, go to the src directory and type make
  (or alternately gmake).  This will create all the executable files
  in the directory bin.  Note that initially directories bin, lib and
  obj are all empty.

- Scripts for running the programs are in directory scripts.  Each
  needs to be edited near the top to specify the correct location
  (give the full path) where you have the bin and scripts directories
  on your system.  Script g3-iterated.csh is generally the best to use
  to make gene predictions from a single genome sequence without other
  data.

- Some scripts (including g3-iterated.csh) use the program elph, which
  needs to be separately downloaded and installed.  You can get it from
  ccb.jhu.edu/software/ELPH/index.shtml

- Help on options and command parameters for each program can be gotten
  by running the program with a -h option.
