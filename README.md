E2iPlayer https://tv.mindigo.hu/ host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/mindigo/archive/master.zip -q -O /tmp/mindigo.zip
unzip -q -o /tmp/mindigo.zip -d /tmp
cp -r -f /tmp/mindigo-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/mindigo*
~~~

restart enigma2 GUI
