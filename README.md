mstools
=======

mytop.ms
--------
The problem: mytop is not showing queries per second (qps) on certain versions of MySQL
This is a drop-in replacement of /usr/bin/mytop tested on on Ubuntu 12.04 3.5.0-17-generic x86_64

The below is a quick-and-dirty way to replicate the functionality changes contained here on other distro/OS.
First install mytop, then run:

    perl -pi -e 's/Questions/Queries/g' /usr/bin/mytop

