The Goal
========

To create all feeds necessary, in order to run gitg3 on CentOS 6.

Done So Far
===========

 * Compile glib.
 * Compile gobject-introspection.
 * Compile vala.
 * Patch libgit2 to make pkgconfig file relocatable (use e.g. gobject-introspection as a reference). See http://github.org/albx79/libgit2.
 * With patched libgit2, compile libgit2-glib.
 * json-glib-1.0
 * libgee-0.8
 ** I had to disable generating introspection (gir) files, because it would insist installing them in /usr/share
 * Atk 2.7.5
 * cairo
 
Still To Do
===========

 * Requested 'gtk+-3.0 >= 3.10.0' but version of GTK+ is 3.4.2
 ** Requested 'pango >= 1.32.4' but version of Pango is 1.30.0
 *** http://ftp.gnome.org/pub/gnome/sources/pango/1.32/pango-1.32.6.tar.xz
 *** needs cairo
 *** needs fontconfig 2.10.91 or newer
 ** Requested 'cairo-gobject >= 1.12.0' but version of cairo-gobject is 1.10.2
 *** (this should be provided by cairo-1.12)
 ** Requested 'gdk-pixbuf-2.0 >= 2.27.1' but version of GdkPixbuf is 2.26.1
 *** http://ftp.gnome.org/pub/GNOME/sources/gdk-pixbuf/2.27/gdk-pixbuf-2.27.1.tar.xz
 * No package 'webkit2gtk-3.0' found

