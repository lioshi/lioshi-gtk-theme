Lioshi Theme
===========

Lioshi is a modern desktop theme suite. Its design is mostly flat with a minimal use of shadows for depth.

Lioshi has been developed primarily with modern GTK3 (GNOME-based) desktop environments in mind, legacy-toolkit and GTK2 environments will not provide an ideal experience, as much of the visual design relies on modern GTK3+ widgets.

Lioshi is distributed under the terms the GNU General Public License (GNU GPL v.3).

###Getting Lioshi

You can download the Lioshi [here](http://lioshi.com) or it clone from the [git repository](https://github.com/lioshi/lioshi-gtk-theme).

###Building Lioshi

You can build and install the Lioshi GTK theme from source:

    ./autogen.sh
    make
    sudo make install

This procedure requires ```autotools``` on your system.

###Installing Lioshi

Alternatively you may install Lioshi with the provided installation script:

    ./install-gtk-theme.sh

-----------



Changes
see _colors.scss

After change scss run:

    sudo sass --update --sourcemap=none . && ./autogen.sh && sudo make && sudo make install
