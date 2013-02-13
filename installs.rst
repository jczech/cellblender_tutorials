.. _install:

*********************************************
MCell Installation
*********************************************

MCell Overview
---------------------------------------------

MCell is run from the command line, whether you are running \*nix (e.g. UNIX,
Linux), Windows, or Mac OS X. For many reasons, we strongly recommend that you
run MCell on \*nix or OS X. MCell does not have a graphical user interface and
cannot be run by double-clicking an icon (Windows users take note). You must be
a registered user to download MCell from our `web site`_.

.. _web site: http://mcell.org/download.html

Installing MCell for Linux/OS X
---------------------------------------------

Download the desired binary file for your system (e.g., MCell v. |release| for
Linux x86).

The binary file that you download is a gzip’ed file with a name that ends in
".gz". Your browser may think that it knows more than you do and automatically
unzip the file without changing its name (this can lead to considerable
confusion).

Assuming that your browser hasn't already done so, unzip the file, e.g.,

::

    gunzip mcell-3.1.998_x86.gz

If this succeeds, the file will no longer have the .gz suffix. If it fails and
you get an error message, it's probably already been unzipped by your browser.
In this case just continue with the next step, but remember to include the
".gz" suffix on the file name.

Rename the file to something more convenient and make it executable, e.g.,

::

    mv mcell-3.1.998_x86 mcell
    chmod a+x mcell

Depending on your preferences, you may want to put the resulting executable
binary in an appropriate place for yourself or all the users of the machine
(e.g., ``/usr/local/bin`` if you have root privileges).

Verify correct function by typing the name of the executable at a command
prompt, e.g.,

::

    mcell

If you have put MCell in an appropriate directory included in your path for
executables, you should see a startup message followed by an error that
indicates no MDL (Model Description Language) file has been specified. MDL
files are used to design and control MCell simulations (see MCell tutorials).

*********************************************
CellBlender Installation
*********************************************

Installing CellBlender
---------------------------------------------

Startup Blender and go to the **File->User Preferences** menu. In the "User
Preferences" control panel choose the **Addons** tab. Click the **Install from
File** button at the bottom of the window. Navigate to the unextracted zip file
that you downloaded (cellblender_v52.zip), select it, and click the **Install
from File** button near the upper-right hand corner.

Activating CellBlender in Blender
---------------------------------------------

Scroll down until you see **Cell Modeling: CellBlender** and select the
checkbox to enable it. Then, click **Save as Default** to enable the addon
permanently in Blender.

*********************************************
DReAMM and PSC DX Installation
*********************************************

DReAMM and PSC DX are no longer actively developed, but will remain available
for download. The installation instructions can be found here_.

.. _here: https://www.mcell.psc.edu/tutorials_old/installs.html



