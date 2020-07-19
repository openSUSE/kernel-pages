---
title: SLE15-SP1-AZURE branch
redirect_from: /branches/SLE15-SP1-AZURE/
---
# SLE15-SP1-AZURE
This is the SLE15 SP1 AZURE kernel branch.

The person in charge of this branch is:
Olaf Hering <[ohering@suse.de](mailto:ohering@suse.de?subject=SLE15-SP1-AZURE%20branch)>

It is the person aboves responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/SLE15-SP1-AZURE)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/SLE15-SP1-AZURE)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/SLE15-SP1-AZURE/standard \
    Kernel:SLE15-SP1-AZURE
zypper in --from Kernel:SLE15-SP1-AZURE kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/SLE15-SP1-AZURE)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/SLE15-SP1-AZURE)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b SLE15-SP1-AZURE
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/SLE15-SP1-AZURE)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/SLE15-SP1-AZURE)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b SLE15-SP1-AZURE
```


