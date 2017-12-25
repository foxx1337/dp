# German - Programmers keyboard layout

This one is inspired by the Romanian - Programmers layout.

- AltGr + a = ä
- AltGr + s = ß
- AltGr + u = ü
- AltGr + o = ö

## Installation

Just copy, patch or overwrite the files in the root of the distro (Ubuntu) with files under the `root`
subdirectory of this repository.

The command to update (though it appears to happen automatically un Ubuntu 17.10 with Mate) the
layouts is:

```bash
sudo dpkg-reconfigure xkb-data
```

## See Also

* https://help.ubuntu.com/community/Custom%20keyboard%20layout%20definitions?action=show&redirect=Howto%3A+Custom+keyboard+layout+definitions
* https://wiki.debian.org/Keyboard#How_to_switch_a_keyboard_layout_in_X11_.2F_graphical_desktop_environment
