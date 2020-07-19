---
title: openSUSE-15.2 branch
redirect_from: /branches/openSUSE-15.2/
---
# openSUSE-15.2
This is the openSUSE Leap 15.2 kernel branch.

The people in charge of this branch are:
Michal Kubecek <[mkubecek@suse.cz](mailto:mkubecek@suse.cz?subject=openSUSE-15.2%20branch)>
Miroslav Benes <[mbenes@suse.cz](mailto:mbenes@suse.cz?subject=openSUSE-15.2%20branch)>

It is the above peoples responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/openSUSE-15.2)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/openSUSE-15.2)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/openSUSE-15.2/standard \
    Kernel:openSUSE-15.2
zypper in --from Kernel:openSUSE-15.2 kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/openSUSE-15.2)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/openSUSE-15.2)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b openSUSE-15.2
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/openSUSE-15.2)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/openSUSE-15.2)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b openSUSE-15.2
```


