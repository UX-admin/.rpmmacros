**NAME**
--------
rpmmacros - macro definitions for building runtime platform RPM packages

**DESCRIPTION**
---------------
In addition to being compiled to build packages in the /usr/src/
directory, the redhat package manager also reads /etc/rpmmacros and
$HOME/.rpmmacros file, and will override, as well as augment built-in
macro definitions with the ones found in the above files.

This repository contains the macro overrides of the rpm built-ins, as well as
additional macro definitions required to build all runtime platform RPM packages
with the **[rpmbuild(8)](https://linux.die.net/man/8/rpmbuild)** command. The _.rpmmacros_ file can be copied
either to one's home, or to the _/etc/_ directory as _/etc/rpmmacros_.

**SEE ALSO**
------------
**[rpmbuild(8)](https://linux.die.net/man/8/rpmbuild)**, **[intro(5)](https://linux.die.net/man/5/intro)**.
