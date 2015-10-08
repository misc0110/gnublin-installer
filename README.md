The Installer for the GNUBLIN Embedded Linux Board consists of two independend programs, the graphical and the commandline installer.

Both programs need root to operate. They can be started with

* **gnublin-installer** for the graphical installer and
* **gnublin-cmdline** for the commandline installer

To generate the binaries from source, you just have to execute make in the source directory. The dependencies are libparted0debian1, libcurl3, libwxgtk2.8-0 and libarchive12 (all, of course, as developer version).

Graphical Installer | Commandline Installer
------------ | -------------
![Graphical Installer for GNUBLIN Embedded Linux Board](http://gnublin-installer.googlecode.com/files/gnublin_installer_screenshot.png) | ![Commandline Installer for GNUBLIN Embedded Linux Board](http://gnublin-installer.googlecode.com/files/gnublin_cmdline_screenshot.png)
