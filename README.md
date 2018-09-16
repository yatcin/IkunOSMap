# IkunOSTile
“**IkunOSTile**”( 「生野スタイル」と読みます )はOpenStreetMapの地図データを使った地図タイルです。<br>
地図データ登録時に付けられた、”**name:en**”タグをオブジェクトのラベルで表示するようにしました。<br>
(“name:en”タグが付けられていない場合は”**name**”タグでラベリングしています。)

# What's IkunOSTile?
[大阪市生野区](https://en.wikipedia.org/wiki/Ikuno-ku,_Osaka)は大阪市の中で最も外国人居住者が多い区です。<br>
生野区在住の外国人にとって使い勝手の良い地図を作りたいとの思いから「IkunOSTile」と名付けました。<br>
("**Ikuno Style**"と"**Ikuno’s Tile**"、”**OpenStreetMap**”の通称 “**OSM**”を掛け合わせています。)

# 使用方法
tileLayerに<br>
`http://tile.yatcin.net/osm_tiles/{z}/{x}/{y}.png`<br>

を指定してください。<br>


```
L.tileLayer('http://tile.yatcin.net/osm_tiles/{z}/{x}/{y}.png').addTo(map);
```

# ライセンス
IkunOSTileはCC-BY--SA 4.0ライセンスでのもとに公開しています。<br>
CC-BY--SA 4.0ライセンス条件を満たす限り、自由な複製・配布・修正を無制限に行うことができます。<br>
タイルを使用時、次のクレジットを表示してください。<br>
`Map data © OpenStreetMap contributors, CC-BY-SA. Map tiles by IkunOSMap Project, under CC-BY-SA 4.0. Data by OpenStreetMap, under ODbL.`<br>

# Maintainers

* Yasuhiro Wada