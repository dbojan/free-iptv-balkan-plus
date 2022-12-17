IPTV players detalied

windows players:

|name|url playlist on the internet|local file m3u|url playlist multiple in input boxes|channel labels|stability|rating|os|free|pro|con|note|epg in general|multple epg in general|single epg url embedded inside m3u file wiht x-tvg url|multiple epg embedded inside m3u file x-tvg url, separated by ","|epg in additional input box|epg in multiple additional input box| 
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
|vlc|+|+|-|+|4|4|windows|+|it support labels|does not support epg||-|-|||||
|kodi|+|+|-|+|4|3.5|windows|+|supports for epg, although single source only|complicated to set up and navigate, single epg source only (minor con)||+|-|+|-|+ (but not both url in m3u and additional box)|-|
|progtv|+|+|+|+|3.5|4|windows|shareware, recording omitted from free version|multiple epg boxes sources|weird navigation, does not play some channels like moviesphere||+|+|-|-|+|+|
|smplayer|-|+|-|+|4|3.9|windows|+|easy navigation in playlist using arrows|cannot open url with m3u||-||||||
|mpv|+|+|-|+|5|4.1|windows|+|rock stable, can record stream|you have to download additional plugins to display list on windows, does not support epg||-||||||
|vlc|+|+|-|+|3.5|3.9|android|+|it support labels|low stability, sometimes hangs||-|-|||||
|kodi|+|+|-|+|4|3.6|android|+|supports for epg, although single source only|complicated to set up and navigate, single epg source only (minor con), forced landscape, paste does not work||+|-|+|-|+ (but not both url in m3u and additional box)|-|
|progtv|+|+|+|+|3.5|4|android|shareware, recording omitted from free version|multiple epg boxes sources|weird navigation, does not play some channels like moviesphere||+|+|-|-|+|+|
|mpv|+|+|-|+|5|4.1|android|+|very stable|does not support epg, you have to open playlist manually each startup|hold on arrow to the right to see the playlist|-||||||
|tivimate|+|+|-|+|4|4|android|shareware, limitation: singe playlist url and single epg inputbox|shows epg|forced landscape mode||+|-|+|-|+|-|


-vlc: 

media/open network stream, or download list (right click, save as, open in vlc)



-mpc-hc, file, quick open file. user agent is not supported. label is not supported.
-mpv. create mpv.conf in mpv subfolder. add --user-agent=android in mpv.conf,
--if you use command line: mpv --user-agent=android file_or_url_address
--if you want playlist in mpv-windows, download config from https://github.com/tomasklaen/uosc

-kodi, supports epg, kinda complicated to setup, and to navigate.
-(SF Vip player)[https://serbianforum.org/threads/sf-vip-plejer.878393/]
-progtv player (shareware)
-smplayer, download m3u file, open file

android players:

-vlc
-kodi
-progtv
-mpv

Wiki is also active https://github.com/dbojan/free-iptv-balkan-plus/wiki
Let me know if you edit it in a meaningfull way.
