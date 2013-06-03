eve-launcher
============

A minimal launcher for the EVE Online client.

It does not support patching at the moment. Only use it if you are
sure your client is up-to-date.

Released under the WTFPL license, version 2.

NOTE: this program comes WITHOUT ANY WARRANTY. I am NOT responsible
for what happens to your account. You have been warned!

Known issues
============

The character name quiz is not implemented at the moment. If you
encounter this issue, try logging in to EVE Gate in your browser from
the same computer, and retry launching the launcher.

Usage
=====

~~~
Usage:
	launcher [-Ww,wine-option...] [eve-options...]

Example:
	launcher -Ww,explorer -Ww,/desktop=foo,1920x1080 /nosplash /noconsole /server:Tranquility
~~~
