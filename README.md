# free-iptv-balkan-plus, bppp
<code><pre>
### What is it:
It is a free IPTV list of Balkan Ex-Yu channels + some free english speaking tv channels

### What to do with it / Installing:

Enter address: https://cutt.ly/bppp
in media player: [mpv](https://mpv.io/)/[vlc](https://www.videolan.org/vlc/)/[kodi](https://kodi.tv/), whichever program you want to use.
You can also save shortcut, which is file that points to same address: 
[download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u) right click, select 'Save Link As'.  

On **android** click and hold on [download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u), and select 'Download link'
If android renames bppp-shortcut.m3u to .txt file, download [bppp-st.txt](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-st.txt) and rename it to bppp-st.m3u
If this fails, use [cx file explorer](https://play.google.com/store/apps/details?id=com.cxinventor.file.explorer) to create 'bppp-st.txt' file in root folder, 
add https://cutt.ly/bppp to it, save it, rename it to 'bppp-st.m3u'.
If it does not work, try adding whole long url: 
https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u
Or type cutt.ly/bppp in web browser and copy long url to bppp-st.m3u
Open shortcut file in media player, like [mpv](https://play.google.com/store/apps/details?id=is.xyz.mpv). 
Put it in root folder, and in mpv click on 'file picker (legacy)'. if you use 'remember choice on next startup' 
it will always start with 'file picker (legacy)'. Use 'back' on android to exit.
See below in 'android' section for more detailed explanation.

You can [download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u) and use it with ['VLC player'](https://www.videolan.org/vlc/).
Or use it in ['Kodi'](https://kodi.tv/) multimedia player.

To use in 'Kodi': settings, enter in the 'simple iptv plugin' URL:
https://cutt.ly/bppp
or the longer version:
https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u

If you are using this on Android TV, you can type it in using tv remote, or use ['Kodi Remote'](https://kodi.wiki/view/Official_Kodi_Remote) 
android app, to send text to 'Kodi player'. or [download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u).

If you wish to save static m3u file: [balkan-plus.m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u), and select 'Save Link As', 
and save the file somewhere.

You can **edit** downloaded static .m3u playlist using [csvEdit_Esmeralda(beta)](https://github.com/dbojan/csvEdit_Esmeralda)

###  EPG (Electronic Program Guide), tv schedule

"Kodi simple iptv client" only supports one epg url at the time. Only one is enabled in the list.

[ip-tv player by BorPas-Soft](https://borpas.info/iptvplayer), supports multi epg, add it in app settings (CTRL+P).
Separate url to epg xml with comma: http://www.something.com/epg1.xml,http://http://www.something.com/epg2.xml
Right click on app, select 'TV Guide', 'Update TV Guide'

ProgTV can add more than one epg sources, you have to add each in the single text box for guide, 
when adding sources, then click update button.

Epg xml addresses:
https://tvprofil.net/xmltv/data/epg_tvprofil.net.xml.gz (balkan channels)
http://cdn.iptvhr.net/tvdata/guide.xml (balkan channels)
https://i.mjh.nz/PlutoTV/all.xml.gz (plutotv)

more info [here](https://github.com/iptv-org/epg)



### List of players that you can use with IPTV list:
#### windows players:

-[vlc](https://www.videolan.org/vlc/): media/open network stream, or download list (right click, save as, open in vlc), does not support epg

-[mpc-hc version by clsid2](https://github.com/clsid2/mpc-hc/), file, quick open file. user agent is not supported. label is not supported., epg is not supported

-[mpv](https://mpv.io/). create mpv.conf in mpv subfolder. add --user-agent=android in mpv.conf, 
 More info on using mpv player:
-If you want playlist in mpv-windows, download .zip and .conf from 
 https://github.com/tomasklaen/uosc . 
-Put unzipped files and .conf in d:\apps\mpv\mpv, if you have installed mpv in d:\apps\mpv .
-If you use command line, you can use it like this: mpv --user-agent=android file_or_url_address
 or add to mpv/mpv.conf this line:
 user-agent=mpv
 this is needed for some channels only.
-does not support epg

-[ip-tv player by BorPas-Soft](https://borpas.info/iptvplayer) supports epg, windows only, freeware

-[kodi](https://kodi.tv/), supports epg, kinda complicated to setup, and to navigate, supports epg

-[SF Vip player](https://serbianforum.org/threads/sf-vip-plejer.878393/)
to add playlist, click on ... on the right, then +user.
Enter name (anything), location (local file or internet address), and user agent (anything, 
for example mpv ). epg support server-enabled only.

-[smplayer](https://www.smplayer.info/), download m3u file, open file, no support for epg
-[progtv player](https://www.progdvb.com/index/progtv/progtv-win) (shareware), win, android, ios

#### android players:
-vlc
-kodi
-progtv

-[mpv](https://play.google.com/store/apps/details?id=is.xyz.mpv)
-see above for how to add shortcut
-While viewing content, click on screen once, then click and hold on  |< or >| at the bottom,
-to show playlist, or click once on |< or >| to go back/forward on list.
 
 More mpv settings, optional:
-Settings/user interface/screen orientation, select device.
-Settings/advanced/edit mpv.conf, add (this is needed for some channels): 
 user-agent=mpv
-Click on save.



###  Channel list sources:

list of free iptv channels: 
https://github.com/iptv-org/iptv
https://github.com/Free-TV/IPTV
https://satelitskiforum.com/index.php?page=Thread&threadID=11945&pageNo=37
https://iptvcat.com

more info on apps: 
https://github.com/iptv-org/awesome-iptv


qr code creator web: https://goqr.me/
[barcode scanner for android](https://play.google.com/store/apps/details?id=com.google.zxing.client.android)
url shortener: https://cutt.ly

web browser players: 
tv balkan uzivo



## qr codes

qr codes for list, short and long. Both are ok. Point your phone camera, or use qr code scanner app

https://cutt.ly/bppp

![qrshort](qrshort.png)

```













```
https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u
![qrlong](qrlong.png)

### updates:
-20221219-1
channels are mostly from web sites, or possibly apps.

-20230805-1
changed list of tv stations

-2023-08-18-1
 added instatv and some foreign channels like rakutenaction.
 
-2023-08-10-1
 added new xmltv epg sources,
 added new channels.
 removed non working lake channels



