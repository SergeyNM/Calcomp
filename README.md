# CALCOMP - PostScript Emulation of some CALCOMP Plotting Commands.

Original Author: John Burkardt

https://people.sc.fsu.edu/~jburkardt/f77_src/calcomp/calcomp.html

## Description from John Burkardt calcomp.html page
calcomp, a FORTRAN77 code which accepts several calls to Calcomp plotter routines, and tries to create a PostScript file corresponding to the desired image.

The Calcomp plotter was an ancient pen and paper plotting device. One memorable feature of the accompanying software was the strange use of the PLOT command, which had arguments X, Y, and IPEN. When IPEN was 2 or 3, the command resulted in pen drawing or movement, but other values of IPEN had special meanings. In particular, the value of 999 was used to terminate the plot. It's bizarre and clunky features like this that stick in one's memory.

This library assumes that the user's input data has been scaled to fit on a standard "portrait style" page of dimensions 8.5 by 11 inches. If the user's data does not fall within this range, the plot will not be drawn correctly.

Licensing:

The computer code and data files described and made available on this web page are distributed under the GNU LGPL license.

Languages:

calcomp is available in a FORTRAN77 version.

Related Data and Programs:

calcomp_test

PS, a data directory which contains some information about and examples of PostScript graphics files.

PS_WRITE, a FORTRAN90 library which can be used to create a PostScript graphics file.

TOMS626, a FORTRAN77 library for computing contour lines of data associated with a triangulated set of points; the contour lines are drawn using calls to Calcomp plotter software.

Reference:

    Calcomp Graphics Functional Software,
    1969

Source Code:

    calcomp.f, the source code.
    calcomp.sh, commands to compile the source code.
