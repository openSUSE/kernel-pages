---
title: vanilla branch
redirect_from: /branches/vanilla/
---
# vanilla
This branch tracks the latest Linus' tree. Except for packaging or
installation problems, please report all issues to the linux-kernel
mailing list.

This branch is automatically updated by a cron job, please contact

Michal Suchánek <[msuchanek@suse.de](mailto:msuchanek@suse.de?subject=vanilla%20branch)>

before commiting anything.


## [packages](https://download.opensuse.org/repositories/Kernel:/vanilla)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/vanilla)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/vanilla/standard \
    Kernel:vanilla
zypper in --from Kernel:vanilla kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/vanilla)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/vanilla)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b vanilla
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/vanilla)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/vanilla)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b vanilla
```


