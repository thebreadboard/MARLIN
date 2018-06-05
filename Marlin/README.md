# MARLIN
Various configuration files for versions of Marlin that I have created from Stock Marlin for my printers

Download and Install Arduino IDE or Visual Studio Code with PlatformIO
Make sure you install the libraries needed including the often forgotten U8glib
to add a library with arduino IDE, goto "Sketch". "Include Libraries", "Library Manager". Search for "U8glib" and then install it.

If you get other missing Libraries when you compile (Depends on your build and platform), just search in the same way for that library and install it too. I beleive PlatformIO does all this automatically for you but if I find out otherwise I will let you know.

Some boards can be updated through the standard USB port (Tevo BlackWidow and MCmaker7 for instance), others need an ISP programmer like the one I use (Pololu PGM03A) or any other supported by the IDE your using
