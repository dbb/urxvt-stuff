# urxvt-stuff 

<http://github.com/dbb/urxvt-stuff>

## Description

This repo contains some urxvt-related resources.

### tabbed.patch

This patch changes the tab bar to look like this:

![Screenshot of the tab bar after patching](raw/master/example.png)

In other words, it replaces `[NEW]` with `+` and starts the numbering at `0` rather than `1`.

To use it:

```
git clone git@github.com:dbb/urxvt-stuff.git
su -c 'patch -p0 urxvt-stuff/tabbed.patch' root
```
You need root permissions to patch the file `/usr/lib/urxvt/perl/tabbed`. If the tabbed file is somewhere else, like `/usr/local`, just edit the patch file.


