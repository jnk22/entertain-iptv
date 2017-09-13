# Entertain IPTV
## Einleitung
Entertain IPTV ist eine Sammlung von Streamlinks, die ausschließlich für Telekom-Kunden mit gebuchter Option EntertainTV zugänglich sind.
<br><br>
Eine ausführliche Anleitung und Beschreibung findet sich auf Kodinerds.net: [Entertain IPTV auf Kodinerds.net](https://missing/)
<br><br>
Dieses Angebot stellt ein Parallelangebot zu [Kodinerds IPTV](https://github.com/jnk22/kodinerds-iptv) mit frei empfangbaren Streams für TV- und Radiosendern dar.
<br><br>
## Beschreibung / Erklärung
Die Listen sind unterteilt in verschiedene Typen, hier gibt es folgende Typen:

* kodi - Für den optimalen Empfang in Kodi, mit Kategorien für TV-Kanäle. Zu benutzen mit beiden Versionen des PVR IPTV Simple Client.
* clean - Basisliste mit Kategorisierung nach Land. Zum Beispiel für den VLC media player optimal.
* pipe - Liste mit Streams für das PVR-Backend Tvheadend. Streams setzen ffmpeg voraus, installiert unter /usr/bin/ffmpeg.

Hinweis: Die Listen kodi, clean und pipe sind inhaltlich identisch.
<br><br>
Jede der Listen ist unterteilt in eine Struktur, die dem Benutzer ein individuelles Angebot ermöglichen soll. Dabei gilt folgende Struktur:
```
- [typ] - beinhaltet alle TV- und Radiosender

- - [typ]_tv - beinhaltet nur TV-Sender

- - - [typ]_tv_main - nur deutsche Hauptsender
- - - [typ]_tv_mainregional - nur deutsche Regionalsender von RTL und SAT.1
- - - [typ]_tv_regional - nur deutsche Regionalsender
- - - [typ]_tv_local - nur deutsche Lokalsender
```

Hinweis: Alle Unterlisten zusammen beinhalten jeweils den gesamten Inhalt der Oberliste.
<br><br>
## Links zu den Listen
### kodi - für PVR IPTV Simple Client mit Inhaltskategorien (Kodi)
* http://bit.ly/et-kodi

  * http://bit.ly/et-kodi-tv

    * http://bit.ly/et-kodi-tv-main
    * http://bit.ly/et-kodi-tv-mainregional
    * http://bit.ly/et-kodi-tv-regional
    * http://bit.ly/et-kodi-tv-local
<br><br>
### clean - Basisliste mit IPTV-Kanälen (VLC media player)
* http://bit.ly/et-clean

  * http://bit.ly/et-clean-tv

    * http://bit.ly/et-clean-tv-main
    * http://bit.ly/et-clean-tv-mainregional
    * http://bit.ly/et-clean-tv-regional
    * http://bit.ly/et-clean-tv-local
<br><br>
### pipe - Basisliste mit IPTV-Kanälen (VLC media player)
* http://bit.ly/et-pipe

  * http://bit.ly/et-pipe-tv

    * http://bit.ly/et-pipe-tv-main
    * http://bit.ly/et-pipe-tv-mainregional
    * http://bit.ly/et-pipe-tv-regional
    * http://bit.ly/et-pipe-tv-local
<br><br>
## Weiterführende Links
* [Aktuelle To-Do Liste](https://github.com/jnk22/entertain-iptv/issues)
* [Entertain IPTV auf Kodinerds.net](https://missing/)
* [Kodinerds IPTV auf Kodinerds.net](https://www.kodinerds.net/index.php/Thread/56713/)
* [Kodinerds IPTV auf GitHub](https://github.com/jnk22/kodinerds-iptv)
