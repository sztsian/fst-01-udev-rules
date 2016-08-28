# fst-01-udev-rules
Udev rules to allow user access fst-01 gpg without root privileges

FST-01 is a tiny USB 32-bit computer, its full name is "Flying Stone Tiny ZERO-ONE" which intended to run Gnuk or NeuG. With Gnuk it can be treated like a GPG smart card. See [this wiki page](http://wiki.seeedstudio.com/wiki/FST-01) if you want to know more.

This rule is aiming at run gpg --card-status and similar commands work without root privileges.

After installing, reload the rules by:

    (sudo) udevadm control --reload-rules

