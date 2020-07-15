---
title: openSUSE-15.1 branch
redirect_from: /branches/openSUSE-15.1/
---
# openSUSE-15.1
This is the openSUSE 15.1 kernel branch.

The persons in charge of this branch are:
Takashi Iwai <[tiwai@suse.de](mailto:tiwai@suse.de?subject=openSUSE-15.1%20branch)>
Petr Tesarik <[ptesarik@suse.cz](mailto:ptesarik@suse.cz?subject=openSUSE-15.1%20branch)>
Oliver Neukum <[oneukum@suse.de](mailto:oneukum@suse.de?subject=openSUSE-15.1%20branch)>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/openSUSE-15.1)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/openSUSE-15.1)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/openSUSE-15.1/standard \
    Kernel:openSUSE-15.1
zypper in --from Kernel:openSUSE-15.1 kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/openSUSE-15.1)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/openSUSE-15.1)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b openSUSE-15.1
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/openSUSE-15.1)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/openSUSE-15.1)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b openSUSE-15.1
```


