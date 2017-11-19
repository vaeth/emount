# emount

(C) Martin Väth (martin at mvath.de).
This project is under the BSD license.

__mount__/__unmount__ (and create/remove) __dm-crypt__ filesystems
according to your `/etc/fstab`

The cryptsetup program or some equivalent script is needed.

For installation, copy the content of `bin/` with executable permission
in your `$PATH`. Then you can get help by running

`emount --man`

To obtain support for __zsh completion__, you can copy the content
of `zsh/` to a directory of your zsh's `$fpath`.

For Gentoo, there is an ebuild in the mv overlay (available over layman).
