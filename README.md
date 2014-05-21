mstools
=======

mytop.ms
--------

This is a drop-in replacement of /usr/bin/mytop on Ubuntu 12.04 3.5.0-17-generic x86_64, to show qps in certain versions of MySQL

In a nutshell:

    perl -pi -e 's/Questions/Queries/g /usr/bin/mytop
