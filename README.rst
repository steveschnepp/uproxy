======
uProxy
======

This is a *caching* micro HTTP proxy. Its main design is "small". That means no extensive
dependencies, no extensive features. 

The goal was to have a apt-get proxy on an embedded NAS with 64MiB RAM and a
200MHz CPU.

Limits
------

It is non-forking, GET-only.
