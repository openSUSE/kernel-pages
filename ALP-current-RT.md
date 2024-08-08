---
title: ALP-current-RT branch
redirect_from: /branches/ALP-current-RT/
---
# ALP-current-RT
The persons in charge of this branch are:
Mel Gorman <[mgorman@suse.de](mailto:mgorman@suse.de?subject=ALP-current-RT%20branch)>
Frederic Weisbecker <[fweisbecker@suse.de](mailto:fweisbecker@suse.de?subject=ALP-current-RT%20branch)>
Yousaf Kaukab <[ykaukab@suse.de](mailto:ykaukab@suse.de?subject=ALP-current-RT%20branch)>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/ALP-current-RT)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/ALP-current-RT)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/ALP-current-RT/standard \
    Kernel:ALP-current-RT
zypper in --from Kernel:ALP-current-RT kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 11.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/ALP-current-RT)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/ALP-current-RT)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b ALP-current-RT
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/ALP-current-RT)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/ALP-current-RT)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b ALP-current-RT
```


