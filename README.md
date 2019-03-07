E2iPlayer https://mytv.telenor.hu/ host

Install:

~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/mytvtelenor/archive/master.zip -q -O /tmp/mytvtelenor.zip
unzip -q -o /tmp/mytvtelenor.zip -d /tmp
cp -r -f /tmp/mytvtelenor-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/mytvtelenor*
~~~

restart enigma2 GUI

![mytvtelenor_channels](https://user-images.githubusercontent.com/6920933/53969947-00be8b80-40fa-11e9-84ed-059061fb10f5.jpg)
