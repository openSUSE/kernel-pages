---
title: stable
redirect_from: /branches/stable/
---
# stable

This is the Stable kernel branch. It contains the latest stable tree
from kernel.org. Use when you want to test latest and relatively stable
kernels.

The person in charge of this branch is: Jiri Slaby
\<[jslaby@suse.com](mailto:jslaby@suse.com?subject=stable%20branch)\>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.

[](https://download.opensuse.org/repositories/Kernel:/stable)

## packages

To install [prebuilt
kernel](https://download.opensuse.org/repositories/Kernel:/stable) from
this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/stable/standard \
    Kernel:stable
zypper in --from Kernel:stable kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

[](https://github.com/openSUSE/kernel-source/tree/stable)

## kernel-source.git

There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/stable)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

    git clone https://github.com/openSUSE/kernel-source -b stable

[](https://github.com/openSUSE/kernel/tree/stable)

## kernel.git

If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/stable)
git repository. This one has the same layout as the upstream kernel.
Clone command:

    git clone https://github.com/openSUSE/kernel -b stable
