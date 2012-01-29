## Cinnamon system monitor extension

cinnamon-extensions-system-monitor was ported from [gnome-shell-system-monitor-applet](https://github.com/paradoxxxzero/gnome-shell-system-monitor-applet) to work in [Cinnamon](http://cinnamon.linuxmint.com/).
It displays system information in Cinnamon status bar, such as memory usage, CPU usage, network rates…

### Install:

[Ubuntu/Linux Mint PPA](https://launchpad.net/~merlwiz79/+archive/cinnamon-ppa)

Dependencies:
    
    python3
    python3-gobject
    libgtop and gir bindings (gir1.2-gtop-2.0, gir1.2-networkmanager-1.0 on Ubuntu)

* Generic: For a generic installation, run the following commands:
  `./autogen.sh --prefix=/usr && make && sudo make install`
  * Make sure you have the `libglib2.0-dev` package (or equivalent for your distribution)
    installed, or else you'll get an error about `GLIB_GSETTINGS`.
* *Please report further links!*


### Original Authors:
[paradoxxxzero](https://github.com/paradoxxxzero)
[yuyichao](https://github.com/yuyichao)
[darkxst](https://github.com/darkxst)
And [many contributors](https://github.com/paradoxxxzero/gnome-shell-system-monitor-applet/contributors)

### License:

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

