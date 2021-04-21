# GNOME Shell Extension - Blur my Shell

A GNOME Shell extension that adds a blur look to different parts of the GNOME Shell, including the top panel, dash and overview.

![Gnome 40](https://user-images.githubusercontent.com/31563930/115416797-5ed65c00-a1f8-11eb-808b-55791c80ac1e.png)

[<img src="https://github.com/aunetx/files_utils/raw/master/get_it_on_gnome_extensions.png" height="100">](https://extensions.gnome.org/extension/3193/blur-my-shell/)

You can now select which part you want to blur, wether or not you want overview animation and there is an option that reduces a lot the artifacts :)

*Note: this extension contains a lot of bugs. If you find one (that is not already reported), please create an issue!*

## Known bugs

### Note

This extension can be buggy, as the gnome-shell's blur implementation is quite flawed in some ways.

However, selecting *no artifacts* in the settings allows the blur to regenerate itself a lot better, at the expense of CPU time (adds ~3% CPU usage for the gnome-shell process in my old Thinkpad).\
**note: in Gnome 40, selecting this option is not possible for the moment**

Selecting another profile might be enought (especially if you have disabled animations), feel free to test!

### List of bugs

- artifacts on blurred parts [gnome shell bug](https://gitlab.gnome.org/GNOME/gnome-shell/-/issues/2857)
- some apps may become transparent, a weird issue...

If you find other bugs, please report them!

## Advanced

### Install from source

To install the latest version (though maybe unstable), use the makefile:

```sh
git clone https://github.com/aunetx/blur-my-shell
cd blur-my-shell
make install
```

And restart GNOME Shell if needed.

### Versions support

The current extension supports those GNOME Shell versions:

- 40 (beta)

Older GNOME versions are supported up to Blur my Shell version 6:

- 3.36
- 3.38

## License

This program is distributed under the terms of the GNU General Public License, version 2 or later.
