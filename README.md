Electron application of [Sugarizer](http://sugarizer.org).
Distributed with Flatpak.

Installation
------------

To install and run as an Electron application:

    $ npm install && npm start

Build a Flatpak application
---------------------------

The easiest way to distribute applications in Linux is with Flatpak.
The following command will install the required dependencies and then
create the Flatpak package:

    $ npm install
    $ npm run build

The Flatpak bundle will appear inside dist/installers/ . This can be
distributed to any Linux64 system.  To install the bundle and run the
application from command-line:

    $ flatpak install --bundle dist/installers/io.atom.electron.sugarizer_master_x64.flatpak
    $ flatpak run io.atom.electron.sugarizer
