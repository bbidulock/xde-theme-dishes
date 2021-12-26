---
layout: default
---
[xde-theme-dishes -- read me first file.  2021-12-08]: #

xde-theme-dishes
===============

Package `xde-theme-dishes-1.2.4` was released under CCPL:cc-by-nc-nd-3.0
license 2021-12-08.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Communications Dish theme.
This theme uses the Squared-green style from the [`xde-styles`][11]
package.

The source for `xde-theme-dishes` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-dishes-1.2.4` package, released 2021-12-08.
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

Please note that xde-theme-dishes is no longer released as
a tarball and is only released as git commits; use:

    $> ./autogen.sh
    $> ./configure --version

to determine the version associated with a given commit in the
checked out working directory.  Note that this is the same version
as executing:

    $> git describe|sed 's,[-_],.,g;s,\.g*,,'

in the checked out working directory.

Note that only HEAD commits are stable: do not attempt to use any
other commit as only HEAD is synchronized with other packages in
the suite.


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

Following are an additional forty wallpapers that may be used to
customize the theme:

![backyard.jpg](images/backyard.jpg "Additional Image #1")
![blackheath.jpg](images/blackheath.jpg "Additional Image #2")
![bradsully.jpg](images/bradsully.jpg "Additional Image #3")
![brocoli.jpg](images/brocoli.jpg "Additional Image #4")
![cakepans.jpg](images/cakepans.jpg "Additional Image #5")
![dishes_frost.jpg](images/dishes_frost.jpg "Additional Image #6")
![dishes_urals.jpg](images/dishes_urals.jpg "Additional Image #7")
![dish_mist.jpg](images/dish_mist.jpg "Additional Image #8")
![dish_sunset.jpg](images/dish_sunset.jpg "Additional Image #9")
![dish_wires.jpg](images/dish_wires.jpg "Additional Image #10")
![dome_dishes.jpg](images/dome_dishes.jpg "Additional Image #11")
![high_dishes.jpg](images/high_dishes.jpg "Additional Image #12")
![hoghorns_millet1.jpg](images/hoghorns_millet1.jpg "Additional Image #13")
![hoghorns_millet2.jpg](images/hoghorns_millet2.jpg "Additional Image #14")
![hoghorns_millet4.jpg](images/hoghorns_millet4.jpg "Additional Image #15")
![hoghorns_millet5.jpg](images/hoghorns_millet5.jpg "Additional Image #16")
![hoghorns_millet6.jpg](images/hoghorns_millet6.jpg "Additional Image #17")
![hoghorns_millet7.jpg](images/hoghorns_millet7.jpg "Additional Image #18")
![hoghorns_millet8.jpg](images/hoghorns_millet8.jpg "Additional Image #19")
![hoghorns_millet9.jpg](images/hoghorns_millet9.jpg "Additional Image #20")
![hoghorns_milletA.jpg](images/hoghorns_milletA.jpg "Additional Image #21")
![hoghorns_milletB.jpg](images/hoghorns_milletB.jpg "Additional Image #22")
![hoghorns_milletD.jpg](images/hoghorns_milletD.jpg "Additional Image #23")
![hoghorn_valley.jpg](images/hoghorn_valley.jpg "Additional Image #24")
![horn_dishes.jpg](images/horn_dishes.jpg "Additional Image #25")
![lightfoot.jpg](images/lightfoot.jpg "Additional Image #26")
![rare_centered.jpg](images/rare_centered.jpg "Additional Image #27")
![rare.jpg](images/rare.jpg "Additional Image #28")
![ryerson.jpg](images/ryerson.jpg "Additional Image #29")
![storm_dishes2.jpg](images/storm_dishes2.jpg "Additional Image #30")
![storm_dishes.jpg](images/storm_dishes.jpg "Additional Image #31")
![teleport.jpg](images/teleport.jpg "Additional Image #32")
![telesat.jpg](images/telesat.jpg "Additional Image #33")
![tower_all.jpg](images/tower_all.jpg "Additional Image #34")
![tower_dishes5.jpg](images/tower_dishes5.jpg "Additional Image #35")
![tower_glow.jpg](images/tower_glow.jpg "Additional Image #36")
![tower.jpg](images/tower.jpg "Additional Image #37")
![tower_mast.jpg](images/tower_mast.jpg "Additional Image #38")
![twin_towers.jpg](images/twin_towers.jpg "Additional Image #39")
![two_hoghorns.jpg](images/two_hoghorns.jpg "Additional Image #40")



[1]: https://github.com/bbidulock/xde-theme-dishes
[2]: https://github.com/bbidulock/xde-theme-dishes/issues
[3]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/RELEASE
[4]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/NEWS
[5]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/TODO
[7]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/INSTALL
[9]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/LICENSE
[10]: https://github.com/bbidulock/xde-theme-dishes/blob/1.2.4/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools
[13]: https://bbidulock.github.io/adwm

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
