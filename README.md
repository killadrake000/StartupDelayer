SUMMARY
==============
This Program automatically start programs with windows, but after a delay.


DESCRIPTION
==============
The project 'StartupDelayer' is a GUI to create a list of programs with their delay.
It is not mandatory, but its easier to work with this, than editing the 'Objects.dat' by hand.

The project 'DelayedLauncher' creates a thread for every entry, which waits the given time, in seconds, and start the Program.

The GUI creates a 'Objects.dat' file, which contains the programs that are to be started.
The following format is used:

\<NAME\>\<PATH TO A DRIVE\>\<DELAY IN SECONDS\>;

e.g.
\<Notepad++\>\<D:\Program Files (x86)\Notepad++\notepad++.exe\>\<45\>;

USE
==============

1. Start "StartupDelayer.exe", add Programs and their delay.
2. Press Save, and close the program.
	- The Program puts the 'objects.dat' into "%appdata%\roaming\StartupDelayer\objects.dat"

3. If it isn't already there, put the 'DelayedLauncher.exe' into your startup folder.
4. DONE!

If you want to change the file afterwards, just run the 'StartupDelayer.exe' again and save the updated list!