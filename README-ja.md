(English version, see [README.md](README.md))

# IkunOSTile
(Ikuno Style)<br>
![Ikuno Style ScreenShot](https://github.com/yatcin/IkunOSMap/blob/master/ikunostile.png "Ikuno Style ScreenShot")<br>
(Ikuno HK Style)<br>
![Ikuno HK STile ScreenShot](https://github.com/yatcin/IkunOSMap/blob/master/ikunostilehk.png "Ikuno HK Style ScreenShot")<br>
<br>
“**IkunOSTile**”( 「生野スタイル」と読みます )はOpenStreetMapの地図データを使った2種類の地図タイルです。<br>
地図データ登録時に付けられた、”**name:en**”、“**name:ja-Hira**”タグをオブジェクトのラベルで表示するようにしました。<br>
・[Ikuno Style]　”**name:en**”タグでラベルを表記します。<br>
・[Ikuno HK Style]　“**name:ja-Hira**”タグでラベルを表記します。(※)<br>
(“**name:en**”、“**name:ja-Hira**”タグが付けられていない場合は”**name**”タグでラベリングしています。)

> **※**
> 住所表記は[郵便番号データ]を使用しています。その他の名称は“**name:ja-Hira**”タグを使用しています。<br>
> ([郵便番号データ]の詳細は[郵便番号データの説明](https://www.post.japanpost.jp/zipcode/dl/readme.html)を参照)

**Notice:** 現在は日本エリアのみの提供となります。

# What's IkunOSTile?
[大阪市生野区](https://ja.wikipedia.org/wiki/Ikuno-ku,_Osaka)は大阪市の中で最も外国人居住者が多い区です。<br>
生野区在住の外国人にとって使い勝手の良い地図を作りたいとの思いから「IkunOSTile」と名付けました。<br>
("**Ikuno Style**"と"**Ikuno’s Tile**"、”**OpenStreetMap**”の通称 “**OSM**”を掛け合わせています。)

# 使用方法
tileLayerに以下を指定してください。<br>

([Ikuno Style]の場合)
```
L.tileLayer('https://tile.yatcin.net/osm_tiles/{z}/{x}/{y}.png').addTo(map);
```

([Ikuno HK Style]の場合)
```
L.tileLayer('https://tile.yatcin.net/osmhk_tiles/{z}/{x}/{y}.png').addTo(map);
```
(“tile layer”の詳細については[leaflet manual page](https://leafletjs.com/)を参照)

IkunOSTileを使用したサンプルページは下記になります。<br>
https://yatcin.la.coocan.jp/ikunosmap/ikunostile2.html

# ライセンス
IkunOSTileはCC-BY--SA 4.0ライセンスのもとで公開しています。<br>
CC-BY--SA 4.0ライセンス条件を満たす限り、自由な複製・配布・修正を無制限に行うことができます。<br>
タイルの使用は自由ですが、使用時は次のクレジットを表示してください。<br>
```
`Map data © OpenStreetMap contributors, CC-BY-SA. Map tiles by IkunOSMap Project, under CC-BY-SA 4.0.`
```

# Maintainers

* Yasuhiro Wada
