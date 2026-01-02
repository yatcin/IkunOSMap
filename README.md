(日本語版は[README-ja.md](README-ja.md)を参照)

# IkunOSTile
![Ikuno Style ScreenShot](https://github.com/yatcin/IkunOSMap/blob/master/ikunostile.png "Ikuno Style ScreenShot")<br>
(Ikuno Style)<br>
![Ikuno HK STile ScreenShot](https://github.com/yatcin/IkunOSMap/blob/master/ikunostilehk.png "Ikuno HK Style ScreenShot")<br>
(Ikuno HK Style)<br>
<br>
We launched “**IkunOSTile**” [Ikunòstáil] : two type of tile layers for foreigners, one is labeled by Roman characters, other one is labeled by Hiragana characters.<br>

Some objects on the OpenStreetMap, are registered with a tag “**name:en**” (English name) or “**name:ja-Hira**” (Japanese name by Hiragana characters),<br>
- [Ikuno Style] layer describes these objects with that English name by Roman characters for labeling.<br>
- [Ikuno HK Style] layer describes these objects with that Japanese name by Hiragana characters for labeling.<br>
(except some objects have no “name:en” or "name:ja-Hira" tag)

**Notice:** We offer only Japan area now.

# Why IkunOSTile?
“**Ikuno Ward**” (or “**Ikuno-Ku**”) is one of 24 wards of Osaka, Japan. And as known the most largest foreigner registrations stay in the city, so we named “IkunOSTile.”<br>
(more information for Ikuno Ward, see at https://en.wikipedia.org/wiki/Ikuno-ku,_Osaka)

# Copyright and License
“**IkunOSTile**” is licensed under **CC BY-SA  4.0**, a copy of which can be found in the **LICENSE** file.

# Usage
Used to load and display tile layers on the map, you just write following line.

(in case of [Ikuno Style])
```
L.tileLayer('https://tile.yatcin.net/osm_tiles/{z}/{x}/{y}.png').addTo(map);
```

(in case of [Ikuno HK Style])
```
L.tileLayer('https://tile.yatcin.net/osmhk_tiles/{z}/{x}/{y}.png').addTo(map);
```

(More details usage about “tile layer”, you can get at [leaflet manual page](https://leafletjs.com/).)

You see sample page
https://yatcin.la.coocan.jp/ikunosmap/ikunostile2.html

# Credit
We require that you use the credit “Map data © OpenStreetMap contributors , CC-BY-SA, Map tiles by IkunOSMap Project,  under CC BY-SA.”
`Map data © OpenStreetMap contributors, CC-BY-SA. Map tiles by IkunOSMap Project, under CC-BY-SA 4.0.`

# Maintainers
* Yasuhiro Wada
