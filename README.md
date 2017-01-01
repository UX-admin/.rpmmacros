<P ALIGN="justify>
	rpmmacros(5) File Formats rpmmacros(5)
</P>
<P ALIGN="left">
	**NAME**
	rpmmacros - macro definitions for building runtime platform RPM packages
	
	**DESCRIPTION**
</P>
<P ALIGN="justify">
	In addition to being compiled to build packages in the _/usr/src/_
	directory, the redhat package manager also reads _/etc/rpmmacros_ and
	_$HOME/.rpmmacros_ file, and will override, as well as augment built-in
	macro definitions with the ones found in the above files.
</P>
<P ALIGN="justify">
	This repository contains the macro overrides of the rpm built-ins, as well as
	additional macro definitions required to build all runtime platform RPM packages
	with the **rpmbuild(1)** command. The _.rpmmacros_ file can be copied
	either to one's home, or to the _/etc/_ directory as _/etc/rpmmacros_.
</P>
<P ALIGN="left">
	**SEE ALSO**
	**rpmbuild(1)**, **intro(5)**.
</P>

































































