---
title: master branch
redirect_from: /branches/master/
---
# master
This is the master kernel branch.  It will eventually be branched into
the next openSUSE kernel release, but for now it tracks the upstream
kernel.org releases.

Use this branch at your own risk and please report bugs against
openSUSE Factory.

The person in charge of this branch is:
Jeff Mahoney <[jeffm@suse.com](mailto:jeffm@suse.com?subject=master%20branch)>
Michal Kubecek <[mkubecek@suse.com](mailto:mkubecek@suse.com?subject=master%20branch)>

It is the above person's responsiblity for checking in this kernel to
the build system, anyone else who wishes to do so, needs to get
permission from them first.

If there are any questions about this branch, please contact the above
mentioned maintainer.


## [packages](https://download.opensuse.org/repositories/Kernel:/HEAD)
To install
[prebuilt kernel](https://download.opensuse.org/repositories/Kernel:/HEAD)
from this branch run

```
zypper ar -f https://download.opensuse.org/repositories/Kernel:/HEAD/default \
    Kernel:HEAD
zypper in --from Kernel:HEAD kernel-default
```

Please note: The packages are built for the distribution they are
targetting. In case of the vanilla and linux-next branches, this is the
latest released openSUSE version. While the packages should work fine on
fine on a distribution that is slightly newer or slightly older,
installing ancient kernels on the latest distributions is asking for
trouble. Same goes for the opposite case, e.g. installing the Factory
kernel on SLES 9.

## [kernel-source.git](https://github.com/openSUSE/kernel-source/tree/master)
There are two SUSE Kernel repositories. Development happens in the
[kernel-source](https://github.com/openSUSE/kernel-source/tree/master)
git repository. This tree is a quile-like series of patches against the
upstream kernel, plus spec files and various scripts. You can clone it
with

```
git clone https://github.com/openSUSE/kernel-source -b master
```

## [kernel.git](https://github.com/openSUSE/kernel/tree/master)
If you just want to hack on the sources and do not need to package the
kernel, use the [kernel](https://github.com/openSUSE/kernel/tree/master)
git repository. This one has the same layout as the upstream kernel. Clone
command:

```
git clone https://github.com/openSUSE/kernel -b master
```


