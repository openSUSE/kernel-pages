---
title: ALP-current branch
redirect_from: /branches/ALP-current/
---
# ALP-current
The person in charge of this branch is:
Takashi Iwai <[tiwai@suse.com](mailto:tiwai@suse.com?subject=ALP-current%20branch)>
Denis Kirjanov <[denis.kirjanov@suse.com](mailto:denis.kirjanov@suse.com?subject=ALP-current%20branch)>
Yousaf Kaukab <[ykaukab@suse.de](mailto:ykaukab@suse.de?subject=ALP-current%20branch)>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/ALP-current)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/ALP-current)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/ALP-current/standard \
    Kernel:ALP-current
zypper in --from Kernel:ALP-current kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 11.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/ALP-current)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/ALP-current)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b ALP-current
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/ALP-current)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/ALP-current)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b ALP-current
```


