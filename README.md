[xde-theme-dishes -- read me first file.  2021-12-08]: #

xde-theme-dishes
===============

Package `xde-theme-dishes-1.2` was released under CCPL:cc-by-nc-nd-3.0
license 2021-12-08.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Communications Dish theme.
This theme uses the Squared-green style from the [`xde-styles`][11]
package.

The source for `xde-theme-dishes` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-dishes-1.2` package, released 2021-12-08.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-dishes.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-dishes` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-dishes.git
    $> cd xde-theme-dishes
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-dishes` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following is a sample screenshot of the theme taken under the [ADWM][13]
window manager:

![adwm.jpg](scrot/adwm.jpg "Wallpaper #1")

Following are the seven wallpapers included in the theme (consisting
primarily of shots I took of microwave towers with hog-horns around
Alberta using an old Canon PowerShot):

![hoghorns_millet3.jpg](images/hoghorns_millet3.jpg "Wallpaper #1")
![hoghorn.jpg](images/hoghorn.jpg "Wallpaper #2")
![oregon-peak.jpg](images/oregon-peak.jpg "Wallpaper #3")
![two_hoghorns2.jpg](images/two_hoghorns2.jpg "Wallpaper #4")
![hoghorns_milletC.jpg](images/hoghorns_milletC.jpg "Wallpaper #5")
![horn_dishes_centered.jpg](images/horn_dishes_centered.jpg "Wallpaper #6")
![relay_dishes.jpg](images/relay_dishes.jpg "Wallpaper #7")



[1]: https://github.com/bbidulock/xde-theme-dishes
[2]: https://github.com/bbidulock/xde-theme-dishes/issues
[3]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/RELEASE
[4]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/NEWS
[5]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/TODO
[7]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/INSTALL
[9]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/LICENSE
[10]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools
[13]: https://bbidulock.github.io/adwm

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
