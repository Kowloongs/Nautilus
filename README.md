# Nautilus

## Synopsis

Nautilus - Nautilus Operating System

## Architecture

Nautilus is an operating system used to power modern servers,
desktops, and embedded platforms. A large community has
continually developed it for more than thirty years. Its
advanced networking, security, and storage features have
made Nautilus the platform of choice for many of the
busiest web sites and most pervasive embedded networking
and storage devices.

For copyright information, please see the file COPYRIGHT in this
directory. Additional copyright information also exists for some
sources in this tree - please see the specific source directories for
more information.

The Makefile in this directory supports a number of targets for
building components (or all) of the Nautilus source tree.  See build(7), config(8),
for more information, including setting make(1) variables.

Source Roadmap:
---------------
```
bin		System/user commands.

cddl		Various commands and libraries under the Common Development
		and Distribution License.

contrib		Packages contributed by 3rd parties.

crypto		Cryptography stuff (see crypto/README).

etc		Template files for /etc.

gnu		Commands and libraries under the GNU General Public License
		(GPL) or Lesser General Public License (LGPL).  Please see
		gnu/COPYING* for more information.

include		System include files.

kerberos5	Kerberos5 (Heimdal) package.

lib		System libraries.

libexec		System daemons.

release		Release building Makefile & associated tools.

rescue		Build system for statically linked /rescue utilities.

sbin		System commands.

secure		Cryptographic libraries and commands.

share		Shared resources.

stand		Boot loader sources.

sys		Kernel sources.

sys/<arch>/conf Kernel configuration files. GENERIC is the configuration
		used in release builds. NOTES contains documentation of
		all possible entries.

tests		Regression tests which can be run by Kyua.  See tests/README
		for additional information.

tools		Utilities for regression testing and miscellaneous tasks.

usr.bin		User commands.

usr.sbin	System administration commands.
```

For information on synchronizing your source tree with one or more of
the Nautilus Project's development branches.


