The Goal
========

To create all feeds necessary, in order to run gitg3 on CentOS 5.

Done So Far
===========

 * Compile glib.
 * Compile gobject-introspection.
 * Compile vala.
 * Patch libgit2 to make pkgconfig file relocatable (use e.g. gobject-introspection as a reference). See http://github.org/albx79/libgit2.
 * With patched libgit2, compile libgit2-glib.

Still To Do
===========

 * Requested 'gtk+-3.0 >= 3.10.0' but version of GTK+ is 3.4.2
 * No package 'webkit2gtk-3.0' found
 * No package 'gee-0.8' found
 * No package 'json-glib-1.0' found

