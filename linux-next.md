---
title: linux-next branch
redirect_from: /branches/linux-next/
---
# linux-next
This branch tracks the linux-next tree maintained by Stephen Rothwell.
This tree is a merge of all changes that will land in the next kernel
version.  For more information about linux-next, see
http://linux.f-seidel.de/linux-next/

Except for packaging or
installation problems, please report all issues to the linux-kernel
mailing list.

This branch is automatically updated by a cron job, please contact

Michal Suchánek <[msuchanek@suse.de](mailto:msuchanek@suse.de?subject=linux-next%20branch)>

before commiting anything.


## [packages](https://download.opensuse.org/repositories/Kernel:/linux-next)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/linux-next)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/linux-next/standard \
    Kernel:linux-next
zypper in --from Kernel:linux-next kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 11.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/linux-next)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/linux-next)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b linux-next
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/linux-next)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/linux-next)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b linux-next
```


