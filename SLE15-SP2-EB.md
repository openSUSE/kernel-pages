---
title: SLE15-SP2-EB branch
redirect_from: /branches/SLE15-SP2-EB/
---
# SLE15-SP2-EB
This is the SLE 15 SP2 EB kernel branch.

The persons in charge of this branch are:
Jiri Kosina <[jkosina@suse.de](mailto:jkosina@suse.de?subject=SLE15-SP2-EB%20branch)>
Joey Lee <[jlee@suse.de](mailto:jlee@suse.de?subject=SLE15-SP2-EB%20branch)>
Gary Lin <[glin@suse.de](mailto:glin@suse.de?subject=SLE15-SP2-EB%20branch)>
Frederic Weisbecker <[fweisbecker@suse.de](mailto:fweisbecker@suse.de?subject=SLE15-SP2-EB%20branch)>
Varad Gautam <[varad.gautam@suse.com](mailto:varad.gautam@suse.com?subject=SLE15-SP2-EB%20branch)>

It is the above persons' responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/SLE15-SP2-EB)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/SLE15-SP2-EB)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/SLE15-SP2-EB/standard \
    Kernel:SLE15-SP2-EB
zypper in --from Kernel:SLE15-SP2-EB kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/SLE15-SP2-EB)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/SLE15-SP2-EB)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b SLE15-SP2-EB
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/SLE15-SP2-EB)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/SLE15-SP2-EB)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b SLE15-SP2-EB
```


