# Awesome Gnome [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of delightful GNOME extensions and applications.

[GNOME](https://www.gnome.org/) (pronounced /ɡˈnoʊm/ or /ˈnoʊm/, a.k.a. GNOME 3) is a desktop environment for GNU/Linux. GNOME is part of the [GNU Project](http://www.gnu.org/) (Free Software Foundation). Default window server has been changed to Wayland; however the lists below are only tested on X server.

## Table of Contents
* [Appearance](#appearance)
  * [Themes](#themes)
  * [Icons](#icons)
* [Extensions](#extensions)
  * [Desktop](#desktop)
  * [Activities](#activities)
  * [Top panel](#top-panel)
  * [Hardware](#hardware)
* [Applications](#applications)
  * [System](#system)
  * [Interface](#interface)
  * [Multimedia](#multimedia)
  * [Utilities](#utilities)
* [Files (Nautilus)](#files-nautilus)
  * [Extensions](#extensions-1)
  * [Actions](#actions)
  * [Emblems](#emblems)
* [License](#license)


## Appearance

### Themes

Themes are stored at `/usr/share/themes/`.

* [Arc Theme](https://github.com/horst3180/Arc-theme) -  Flat design with light and dark variants.


### Icons

User icons are stored at `~/.local/share/icons/`. Global icons are stored at `/usr/share/icons/`.

* [Elementary Icons](https://github.com/elementary/icons) - Originally designed for Elementary OS. Vibrant color.
* [Vertex](https://github.com/horst3180/vertex-icons) - Notable for its neutral folder color.

## Extensions

[GNOME Extensions](https://extensions.gnome.org/) gives back the functionality it should have. Use **Web** browser to manage and update extensions.

Be sure to turn off shell version check so the extension won't break after shell update:

```
gsettings set org.gnome.shell disable-extension-version-validation "true"
```

### Desktop

* [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/) - Always access application dock on the left side of the screen.
* [Workspaces to Dock](https://extensions.gnome.org/extension/427/workspaces-to-dock/) - Always access workspace dock on the right side of the screen.
* [Pixel Saver](https://extensions.gnome.org/extension/723/pixel-saver/) - Hide GTK2 title bar to save pixels when maximized.

### Activities

* [windowNavigator](https://extensions.gnome.org/extension/10/windownavigator/) - Use <kbd>Alt</kbd>+Num to switch to windows in Overview.
* [Quick Close in Overview](https://extensions.gnome.org/extension/352/middle-click-to-close-in-overview/) - Close windows with a mouse middle click when in Overview.
* [Appfolders Management](https://extensions.gnome.org/extension/1217/appfolders-manager/) - Easily group apps into folders with right-click menu in Applications view.

### Top panel

* [Top Panel Workspace Scroll](https://extensions.gnome.org/extension/701/top-panel-workspace-scroll/) - Change workspaces by mouse scrolling over the top panel.
* [Activities configurator](https://extensions.gnome.org/extension/358/activities-configurator/) - Replace the text "Activities" on the top left corner with custom text/icon and make top panel tranparent.
* [TopIcons Plus](https://extensions.gnome.org/extension/1031/topicons/) - Shows legacy tray icons on top, like Dropbox.
* [Places Status Indicator](https://extensions.gnome.org/extension/8/places-status-indicator/): Add a Nautilus bookmark menu.
* [Files Menu](https://extensions.gnome.org/extension/907/files-menu/):
Quickly browse your file system and open files through a menu.
* [Recent(Item)s](https://extensions.gnome.org/extension/977/recent-items/): Add an indicator in top panel to list recently opened files.
* [Window Corner Preview](https://extensions.gnome.org/extension/1227/window-corner-preview/) - Add picture-in-picture preview for any window at cornor of the screen. Useful for watching videos and monitoring window status.
* [Media player indicator](https://extensions.gnome.org/extension/55/media-player-indicator/) - Show music control with current artist name, music name.
* [Screenshot Tool](https://extensions.gnome.org/extension/1112/screenshot-tool/): Conveniently create, copy, store and upload full, window and area screenshots.
* [EasyScreenCast](https://extensions.gnome.org/extension/690/easyscreencast/) - Utilize built-in screen recording function into a easy-to-use panel icon.
* [Todo.txt](https://extensions.gnome.org/extension/570/todotxt/) - Create simple todo list stored as `todo.txt`.
* [Input Method Panel](https://extensions.gnome.org/extension/261/kimpanel/) - For fcitx (Chinese input method).
* [Argos](https://extensions.gnome.org/extension/1176/argos/) - Make custom top panel extension using Bash script.

### Hardware

* [Suspend Button](https://extensions.gnome.org/extension/826/suspend-button/) - Add suspend button in the status menu. Otherwise you hold <kbd>Alt</kbd> key to show it.
* [Turn off Display](https://extensions.gnome.org/extension/897/turn-off-display/) - Adds a button to the status menu to turn off the screen.
* [Toggle Touchpad](https://extensions.gnome.org/extension/935/toggle-touchpad/): Switch touchpad on and off to prevent accidentally triggering.
* [Sound Output Device Chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/) - Shows a list of sound output devices to select from.

## Applications

Below are GTK+ 3 apps (new header bar and dark theme available).

### System

* [Tilix](https://gnunn1.github.io/tilix-web/) - Tiling terminal with tranparent background.
* [System Monitor](https://wiki.gnome.org/Apps/SystemMonitor) - Watch CPU, memory, network usages, process and disks usage.
* [Disk Usage Analyzer (baobab)](https://wiki.gnome.org/Apps/Baobab) - Examine disk usage with pie charts.
* [Packages & Package Updater (PackageKit)](https://www.freedesktop.org/software/PackageKit/) - Graphical interface for various package manager like `apt`, `pacman` etc.
* [Font Manager](https://fontmanager.github.io/) - Manage fonts.
* [gitg](https://wiki.gnome.org/Apps/Gitg) - Git graphical client.
* [Meld](http://meldmerge.org/) - Compare directories and files.
* [Backups (Déjà Dup)](https://wiki.gnome.org/Apps/DejaDup) - An easy way to backup the disk using **duplicity**. It only records differences of files. It integrates well with Nautilus.

### Interface

* [Easystroke](https://github.com/thjaeger/easystroke/wiki) - Define your mouse gestures to trigger keyboard shortcuts.
* [GNOME Pie](https://simmesimme.github.io/gnome-pie.html) - Shows pie menus of different kinds like alt-tab application menu, bookmarked places menu (needs [fix](https://gist.github.com/tanyuan/01dfc1f283a4de578968865db6b239f0)), media menu and more. It plays well with **Easystroke**.

### Multimedia

* [Gnote](https://wiki.gnome.org/Apps/Gnote) - Take text notes. A port of Tomboy to C++.
* [gThumb](https://wiki.gnome.org/Apps/gthumb) - View photos in native folder structures.
* [Lollypop](https://gnumdk.github.io/lollypop-web/) - iTune-like music player.
* [Pitivi](http://www.pitivi.org/) - Simple video editor.
* [MyPaint](http://mypaint.org/) - Pleasant drawing app with Wacom stylus.

### Utilities

* [GPaste](https://github.com/Keruspe/GPaste) - View and edit clipboard history with additional Gnome Shell Extension.
* [Gcolor3](https://hjdskes.github.io/projects/gcolor3/) - A simple Color selector.
* [Peek](https://github.com/phw/peek) - GIF screen recorder.

## Files (Nautilus)

Package names are according to Arch Linux Packages.

### Extensions

* `sushi` - Preview the selected folder or file by hitting <kbd>Space</kbd>.
* [nautilus-git](https://github.com/bil-elmoussaoui/nautilus-git) - Display Git branches and shortcut to remote repo in status bar.
* [nautilus-terminal](http://projects.flogisoft.com/nautilus-terminal/) - Embed a terminal that will change directory when you browse. You can toggle the terminal by <kbd>F4</kbd>.

### Actions

Actions for right-click menu. More custom actions can be configured through `nautilus-actions`.

* `nautilus-open-terminal` - Open a terminal at the current directory.
* `nautilus-image-tools` - A bunch of image manipulation tools like resize, convert, flip etc.
* `nautilus-pdf-tools` - A bunch of PDF manipulation tools like extract pages, remove pages, join PDFs, convert to PNG etc.
* `nautilus-renamer` - Batch rename for selected files with rules.

### Emblems

Read [How to manually add emblems in nautilus](http://www.webupd8.org/2011/12/how-to-manually-add-emblems-in-nautilus.html). Basically install `python2-nautilus` and:

```
cp nautilus_emblems_menu.py /usr/share/nautilus-python/extensions/
```

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Shan-Yuan Teng](http://tengshanyuan.com/) has waived all copyright and related or neighboring rights to this work.
