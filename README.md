# collectd-rpm

Repository which provides a sane RPM SPEC file for building RPMs on RHEL/CentOS
Linux.

# Setting up the toolchain

In order to compile a sane RPM file it's recommended to use the toolchain of
mock to build the rpms. mock is the same tool which is being used to build the
RPMs of Fedora, CentOS and EPEL. Basically, it sets up a chroot environment,
changes into it and runs the required compile steps.

The chroot environment is provided every time you start a new build. This
make sure that your environment is clean and only sane dependencies are used
to link the binaries.

# Getting SRPMs and binaries

I will provide binary and source packages frequently at

[rpm.acme-services.org](http://rpm.acme-services.org)

# Contributors

* Thanks to jeff.oconnell@gmail.com for the initial amqp support

# Bugs and support

This package will have updates for sure, if you encounter a problem, please
send me a pull request on my

[GitHub repository](https://github.com/rhaen/collectd-rpm)

--rhaen
