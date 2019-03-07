E2iPlayer https://mytv.telenor.hu/ host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/mytvtelenor/archive/master.zip -q -O /tmp/mytvtelenor.zip
unzip -q -o /tmp/mytvtelenor.zip -d /tmp
cp -r -f /tmp/mytvtelenor-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/mytvtelenor*
~~~

restart enigma2 GUI
