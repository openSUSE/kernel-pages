---
title: SLE12-SP5 branch
redirect_from: /branches/SLE12-SP5/
---
# SLE12-SP5
This is the SLE 12 SP5 kernel branch.

The persons in charge of this branch are:
Denis Kirjanov <[dkirjanov@suse.com](mailto:dkirjanov@suse.com?subject=SLE12-SP5%20branch)>
Petr Tesarik <[ptesarik@suse.cz](mailto:ptesarik@suse.cz?subject=SLE12-SP5%20branch)>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/SLE12-SP5)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/SLE12-SP5)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/SLE12-SP5/standard \
    Kernel:SLE12-SP5
zypper in --from Kernel:SLE12-SP5 kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/SLE12-SP5)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/SLE12-SP5)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b SLE12-SP5
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/SLE12-SP5)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/SLE12-SP5)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b SLE12-SP5
```

## live patches
Sources of kernel live patch updates [SLE12-SP5_Update_25](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_25) [SLE12-SP5_Update_24](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_24) [SLE12-SP5_Update_23](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_23) [SLE12-SP5_Update_22](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_22) [SLE12-SP5_Update_21](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_21) [SLE12-SP5_Update_20](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_20) [SLE12-SP5_Update_19](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_19) [SLE12-SP5_Update_18](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_18) [SLE12-SP5_Update_17](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_17) [SLE12-SP5_Update_16](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_16) [SLE12-SP5_Update_15](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_15) [SLE12-SP5_Update_14](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_14) [SLE12-SP5_Update_13](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_13) [SLE12-SP5_Update_12](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_12) [SLE12-SP5_Update_11](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_11) [SLE12-SP5_Update_10](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_10) [SLE12-SP5_Update_9](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_9) [SLE12-SP5_Update_8](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_8) [SLE12-SP5_Update_7](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_7) [SLE12-SP5_Update_6](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_6) [SLE12-SP5_Update_5](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_5) [SLE12-SP5_Update_4](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_4) [SLE12-SP5_Update_3](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_3) [SLE12-SP5_Update_2](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_2) [SLE12-SP5_Update_1](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_1) [SLE12-SP5_Update_0](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP5_Update_0)
