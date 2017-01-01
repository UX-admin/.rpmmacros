<P ALIGN="justify>
	rpmmacros(5) File Formats rpmmacros(5)
</P>

**NAME**
rpmmacros - macro definitions for building runtime platform RPM packages

**DESCRIPTION**

<P ALIGN="justify">
	In addition to being compiled to build packages in the /usr/src/
	directory, the redhat package manager also reads /etc/rpmmacros and
	$HOME/.rpmmacros_ file, and will override, as well as augment built-in
	macro definitions with the ones found in the above files.
</P>
<P ALIGN="justify">
	This repository contains the macro overrides of the rpm built-ins, as well as
	additional macro definitions required to build all runtime platform RPM packages
	with the **rpmbuild(1)** command. The .rpmmacros file can be copied
	either to one's home, or to the /etc/ directory as /etc/rpmmacros.
</P>

**SEE ALSO**
**rpmbuild(1)**, **intro(5)**.
































































