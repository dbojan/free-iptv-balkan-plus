# free-iptv-balkan-plus, bppp


### What is it:
- definition: iptv list is a list of network address for free tv channels, like youtube playlist
- This is a list of channels for Balkan area: Ex-Yu channels + some free english speaking tv channels with commercial breaks
  
### Lists included:
- balkan plus: balkan (serbian/croatian/bosnian) channels + english speaking channels with commercial breaks
  - short url: https://cutt.ly/bppp
  - long url: https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/main/balkan-plus.m3u

- samo domaći kanali
  - short url: https://cutt.ly/bddd
  - long url: https://raw.githubusercontent.com/dbojan/free-iptv-balkan-plus/refs/heads/main/balkan-plus-samo-domaci.m3u

### How to use it:

### Windows:

I use editor [csvEdit_Esmeralda](https://github.com/dbojan/csvEdit_Esmeralda) to open m3u list, and then double click on row to view channel.
Requires [mpv](https://mpv.io/) player and ffmpeg to be installed, preferrably in d:\apps.

List of usable media players: 
- [vlc](https://www.videolan.org/vlc/) start vlc, media/open network stream, add https://cutt.ly/bppp
- [ip-tv player by BorPas-Soft](https://borpas.info/iptvplayer) supports epg, windows only, freeware
  - to set user agent in windows, in 'IpTvPlayer.User.ini' file, under [Settings] add: 
   - setvlcvars="http-user-agent=Android"
- [SF Vip player](https://serbianforum.org/threads/sf-vip-plejer.878393/)
  - to add playlist, click on ... on the right, then +user.
  - Enter name (anything), location (local file or internet address), and user agent (anything, for example mpv)
  - epg support server-enabled only.
- [smplayer](https://www.smplayer.info/), download m3u file, open file, no support for epg
- [progtv player](https://www.progdvb.com/index/progtv/progtv-win) (shareware, minor limitations, like no recording), win, android, ios
- [mpc-hc version by clsid2](https://github.com/clsid2/mpc-hc/), file, open file-url, add long url. Not supported: short url, user agent, epg
- [kodi](https://kodi.tv/): install simple iptv plugin, add address: https://cutt.ly/bppp. Complicated to setup
- [mpv](https://mpv.io/), command line mostly.


### Android/TV
- sparkle tv, very good, supports encrypted channels, supports auto refresh with 3 hours minimal time. Can only add one playlist at a time, 
- ott navigator, supports encrypted channels, DOES NOT support auto refresh in free version, can add multiple playlist, one active at a time.
- progtv, 3 seconds delay at a start in trial version, supports auto refres with 1 hour minimal time, multiple lists support, one active at a time I think.
- [progtv player](https://www.progdvb.com/index/progtv/progtv-win) settings
  - add sources: https://cutt.ly/bppp includes english channnels, or https://cutt.ly/bddd (domaca)
  - use **arrow up** or **arrow down** on the remote to move through channels
  - if there is no channel after wake from sleep mode, press **ok** on remote a couple of times, or go up/down channel while wifi is restored
   - Recommended settings: **User interface**/more options/show confirmation on exit=off
    - show information after selecting channel from the list=on
   - **Controls** / Start program after boot=on
    - close list after selecting channel=on
    - cyclic=on (on the Last channel, when you press down key, program will go back to channel 1)
    - next channel by up key=off (use up key to go up the list, down key to go down the list, on the list of channels)
   - Optional: **Channel list**/History=off (this is for the list)
    - show channel numbers=off
   - **in list property**/update every = 2hr (this is optional, default is 10 hrs)
 

 - [orion tv android app](https://play.google.com/store/apps/details?id=rs.maketv.orionott), rotating list of free regional channels
   - install [DNS66](https://github.com/julian-klode/dns66), to block adds
   - set dns66 to autostart, add [adguard](https://adguard-dns.io/kb/general/dns-providers/) dns ip: 94.140.14.14, or 94.140.14.15 (optional?)
   - recommend to use orion app as a guest, you get more channels?
   - after starting orion app, press ok on the remote, use **channel+** and **channel-** to move through channels

- dango player: unable to test latest version on android tv (android 7), older version have problem with lists, does not support encrypted channels
- fermata, support sftp, does not support encrypted channels
- 'televizio', 'm3u app', 'iptv smarters', do not support encrypted channels
- tivimate: paying required for: resume last channel, autostart, update list from app, more than one list. Not recommended.  Supports encrypted channels
- kodi does not support encrypted channels?, big
- mpv and vlc players are also available for android.


###  EPG (Electronic Program Guide), tv schedule

- Note: epg currently it is not added directly to these list, cause I did not use it much, and I think it uses a lot of memory on Android TV.
- [ip-tv player by BorPas-Soft](https://borpas.info/iptvplayer), windows only, supports multi epg, add it in app settings (CTRL+P).
Separate url to epg xml with comma: http://www.something.com/epg1.xml,http://http://www.something.com/epg2.xml
Right click on app, select 'TV Guide', 'Update TV Guide'
- [kodi](https://kodi.tv/) only supports one epg url at the time. 
- ProgTV can add more than one epg sources, you have to add each in the single text box for guide, 
when adding sources, then click update button.

Epg xml addresses examples:
- https://i.mjh.nz/PlutoTV/all.xml.gz
- https://i.mjh.nz/SamsungTVPlus/all.xml.gz
- https://tvprofil.net/xmltv/data/epg_tvprofil.net.xml.gz
- https://www.bevy.be/bevyfiles/croatia.xml.gz
- https://www.bevy.be/bevyfiles/bosnia.xml.gz
- https://www.bevy.be/bevyfiles/serbia.xml
- https://www.bevy.be/bevyfiles/montenegropremium.xml.gz

more info [here](https://github.com/iptv-org/epg)


###  Channel list sources:
list of free iptv channels:   
https://github.com/iptv-org/iptv  
https://github.com/Free-TV/IPTV  
https://satelitskiforum.com  
https://iptvcat.com  
ja gledam    balkan tv uzivo

more info on apps: 
https://github.com/iptv-org/awesome-iptv

- qr code creator web: https://goqr.me/
- [barcode scanner for android](https://play.google.com/store/apps/details?id=com.google.zxing.client.android)
- url shortener: https://cutt.ly

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

2025-03-30-1  
-update domaci  
-removed domaci-mini, merged with domaci  

2024-12-1-1
- new list grouping/edit
- site edit

2024-10-31-1
- fixed hr

2024-10-30-1
- fixed pl

2024-10-20-1
- update list: sort series, remove some 'stream ended' channels

2024-09-28-1
- update list, epg urls

2024-09-07-2
- list updated foreign

2024-09-07-1
- list updated foreign

2024-09-01-1
- list updated

2024-07-21-1
- updated links.

2024-02-27-1
- removed horr.

2024-01-20-2
- uploaded correct file
- apparently it takes about 10min for link (raw) to update ...

2024-01-20
- update list
- renamed kids and nature channel names

2023-08-10-1
- added new xmltv epg sources,
- added new channels.
- removed non working lake channels

20230805-1
- changed list of tv stations

20221219-1
- channels are mostly from web sites, or possibly apps.



 


 



