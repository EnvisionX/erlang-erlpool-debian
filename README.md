# Debianization for the Erlang Resource Pool Library

The repo contains so called DEBIAN directory with
scripts and configs needed to package the
[erlpool](http://sourceforge.net/projects/erlpool/)
library into a DEB package for the Debian Wheezy distro.

Resource pool project is written in Erlang as a tiny library.
The goal of the tool is reduce the overhead of creating new
resources by reusing of the same resources among multiple
processes. Achieving result is better performance and
throughput. The resource pool was inspired by Java Apache's
commons pool and adopts API and main principals from this
project. Database connection is most popular example for
pooling resource.
