---
title: SLE12-SP4
redirect_from: /branches/SLE12-SP4/
---
# SLE12-SP4

This is the SLE12-SP4 kernel branch.

The person in charge of this branch is: Denis Kirjanov
\<[dkirjanov@suse.com](mailto:dkirjanov@suse.com?subject=SLE12-SP4%20branch)\>
Petr Tesarik
\<[ptesarik@suse.cz](mailto:ptesarik@suse.cz?subject=SLE12-SP4%20branch)\>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.

[](https://download.opensuse.org/repositories/Kernel:/SLE12-SP4)

## packages

To install [prebuilt
kernel](https://download.opensuse.org/repositories/Kernel:/SLE12-SP4)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/SLE12-SP4/standard \
    Kernel:SLE12-SP4
zypper in --from Kernel:SLE12-SP4 kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

[](https://github.com/openSUSE/kernel-source/tree/SLE12-SP4)

## kernel-source.git

There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/SLE12-SP4)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

    git clone https://github.com/openSUSE/kernel-source -b SLE12-SP4

[](https://github.com/openSUSE/kernel/tree/SLE12-SP4)

## kernel.git

If you just want to hack on the sources and do not need to package the
kernel, use the
[kernel](https://github.com/openSUSE/kernel/tree/SLE12-SP4) git
repository. This one has the same layout as the upstream kernel. Clone
command:

    git clone https://github.com/openSUSE/kernel -b SLE12-SP4

## live patches

Sources of kernel live patch updates
[SLE12-SP4\_Update\_14](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_14)
[SLE12-SP4\_Update\_13](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_13)
[SLE12-SP4\_Update\_12](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_12)
[SLE12-SP4\_Update\_11](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_11)
[SLE12-SP4\_Update\_10](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_10)
[SLE12-SP4\_Update\_9](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_9)
[SLE12-SP4\_Update\_8](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_8)
[SLE12-SP4\_Update\_7](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_7)
[SLE12-SP4\_Update\_6](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_6)
[SLE12-SP4\_Update\_5](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_5)
[SLE12-SP4\_Update\_4](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_4)
[SLE12-SP4\_Update\_3](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_3)
[SLE12-SP4\_Update\_2](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_2)
[SLE12-SP4\_Update\_1](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_1)
[SLE12-SP4\_Update\_0](https://github.com/SUSE/kernel-livepatch/tree/SLE12-SP4_Update_0)

