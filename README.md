eve-launcher
============

A minimal launcher for the EVE Online client.

It does not support patching at the moment. Only use it if you are
sure your client is up-to-date.

Released under the WTFPL license, version 2.

NOTE: this program comes WITHOUT ANY WARRANTY. I am NOT responsible
for what happens to your account. You have been warned!

Usage
=====

~~~
cd /path/to/my/eve
WINEPREFIX=/my/wine/prefix /path/to/eve-launcher/launcher <client_options…>
~~~

Examples
========

~~~
cd ~/eve
~/eve-launcher/launcher /server:Tranquility /nosplash /noconsole /end /LUA:OFF
~~~