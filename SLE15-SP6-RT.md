---
title: SLE15-SP6-RT branch
redirect_from: /branches/SLE15-SP6-RT/
---
# SLE15-SP6-RT
The persons in charge of this branch are:
Mel Gorman <[mgorman@suse.de](mailto:mgorman@suse.de?subject=SLE15-SP6-RT%20branch)>
Petr Tesarik <[petesarik@suse.de](mailto:petesarik@suse.de?subject=SLE15-SP6-RT%20branch)>
Frederic Weisbecker <[fweisbecker@suse.de](mailto:fweisbecker@suse.de?subject=SLE15-SP6-RT%20branch)>
Jeffrey Cheung <[jcheung@suse.com](mailto:jcheung@suse.com?subject=SLE15-SP6-RT%20branch)>

It is the above persons' responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/SLE15-SP6-RT)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/SLE15-SP6-RT)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/SLE15-SP6-RT/pool \
    Kernel:SLE15-SP6-RT
zypper in --from Kernel:SLE15-SP6-RT kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 11.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/SLE15-SP6-RT)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/SLE15-SP6-RT)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b SLE15-SP6-RT
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/SLE15-SP6-RT)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/SLE15-SP6-RT)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b SLE15-SP6-RT
```

## live patches
Sources of kernel live patch updates [SLE15-SP6-RT_Update_16](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_16) [SLE15-SP6-RT_Update_15](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_15) [SLE15-SP6-RT_Update_14](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_14) [SLE15-SP6-RT_Update_13](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_13) [SLE15-SP6-RT_Update_12](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_12) [SLE15-SP6-RT_Update_11](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_11) [SLE15-SP6-RT_Update_10](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_10) [SLE15-SP6-RT_Update_9](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_9) [SLE15-SP6-RT_Update_8](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_8) [SLE15-SP6-RT_Update_7](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_7) [SLE15-SP6-RT_Update_6](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_6) [SLE15-SP6-RT_Update_5](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_5) [SLE15-SP6-RT_Update_4](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_4) [SLE15-SP6-RT_Update_3](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_3) [SLE15-SP6-RT_Update_2](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_2) [SLE15-SP6-RT_Update_1](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_1) [SLE15-SP6-RT_Update_0](https://github.com/SUSE/kernel-livepatch/tree/SLE15-SP6-RT_Update_0)
