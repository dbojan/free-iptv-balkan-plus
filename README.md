# free-iptv-balkan-plus
<code><pre>
### What is it:
It is a free IPTV list of Balkan Ex-Yu channels + some free english speaking tv channels

### What to do with it / Installing:

Enter address: https://cutt.ly/bppp
in media player: mpv/vlc/kodi, whichever program you want to use.
You can also save shortcut, which is file that points to same address: 
[download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u) right click, select 'Save Link As'.
On android click and hold, and select 'Download link' or create 'bppp-st.txt' file, add https://cutt.ly/bppp to it, save, rename to 'bppp-st.m3u', using 'cx file explorer'
And open shortcut file in media player, like mpv. see below in 'android' section for more detailed explanatin.

If you wish to save static m3u file: [balkan-plus.m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u), and select 'Save Link As', 
and save the file somewhere.

You can use it with ['VLC player'](https://www.videolan.org/vlc/).

Or use it in ['Kodi'](https://kodi.tv/) multimedia player.

To use in 'Kodi': settings, enter in the 'simple iptv plugin' URL:
https://cutt.ly/bppp
or the longer version:
https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u

If you are using this on Android TV, you can type it in using tv remote, or use ['Kodi Remote'](https://kodi.wiki/view/Official_Kodi_Remote) 
android app, to send text to 'Kodi player'.  

You can **edit** downloaded static .m3u playlist using [csvEdit_Esmeralda(beta)](https://github.com/dbojan/csvEdit_Esmeralda)

###  EPG (Electronic Program Guide), tv schedule

**note: epg does not currently work.**
"Kodi simple iptv client" only supports one epg url at the time. Only one is enabled in the list.

ProgTV can add more than one epg sources, you have to add each in the single text box for guide, 
when adding sources, then click update button.

List EPG URLS can be found [here](https://github.com/iptv-org/epg), my shorter versions [here](short)


### List update dates:
-update 2023-08-18-1
 added instatv and some foreign channels like rakutenaction.

-update: 20230805-1
changed list of tv stations

-update: 20221219-1
channels are mostly from web sites, or possibly apps.


### List of players that you can use with IPTV list:
#### windows players:

-vlc: media/open network stream, or download list (right click, save as, open in vlc)

-mpc-hc, file, quick open file. user agent is not supported. label is not supported.

-mpv. create mpv.conf in mpv subfolder. add --user-agent=android in mpv.conf, 
 More info on using mpv player:
-If you want playlist in mpv-windows, download .zip and .conf from 
 https://github.com/tomasklaen/uosc . 
-Put unzipped files and .conf in d:\apps\mpv\mpv, if you have installed mpv in d:\apps\mpv .
-If you use command line, you can use it like this: mpv --user-agent=android file_or_url_address
  
-kodi, supports epg, kinda complicated to setup, and to navigate.

-(SF Vip player)[https://serbianforum.org/threads/sf-vip-plejer.878393/]
to add playlist, click on ... on the right, then +user.
Enter name (anything), location (local file or internet address), and user agent (anything, 
for example mpv )

-progtv player (shareware)

-smplayer, download m3u file, open file

#### android players:
-vlc
-kodi
-progtv

-mpv
How to easier open url on start, without typing it in every time:
-Use [cx file explorer](https://play.google.com/store/apps/details?id=com.cxinventor.file.explorer), create text file named 'bppp-st.txt' in the root of the phone.
-Add this text inside: https://cutt.ly/bppp
-Rename file to 'bppp-st.m3u'. 
-Or [download shortcut m3u](https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/other/bppp-shortcut.m3u)
-Save file. After starting mpv on android, open this file. You can create shortcut m3u file using 
-Click on file picker to open .m3u saved on device. No epg support yet.

While viewing content, click on screen once, then click and hold on  |< or >| at the bottom,
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
