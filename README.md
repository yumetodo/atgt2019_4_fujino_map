# 2019年12月 atgt2019 4匁 藤野駅→緑のラブレター 愛の鐘

https://yumetodo.github.io/atgt2019_4_fujino_map/index.html

電子国土地理院の上に2019年12月にatgt2019 4匁のガムテ探しに藤野駅→緑のラブレター 愛の鐘に行ったときの登山ルートを作図します。

記録記事は

atgt2019 4匁勇者記録 - yumetodoの旅とプログラミングとかの記録
https://yumetodo.hateblo.jp/entry/2019/12/23/024751

にあります。

作図データはスタイル付きGeoJSONです

- スタイルつき GeoJSON 規約  
https://github.com/gsi-cyberjapan/geojson-with-style-spec

## 地図の中心点、ズームの変更

URL末尾に`?longitude=35.858309&latitude=138.989754&zoom=12`のようにパラメータをつけることで変更された状態のものにアクセスできるようになります。

ただし**Internet Explorer 11を含む**古いブラウザでは利用できません(無視されます)。利用できるかは  
[URLSearchParams.get() - Web APIs | MDN](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams/get#Browser_compatibility)  
を確認してください。

- `longitude` (default: `35.858309`): 緯度。`-90 <= longitude <= 90`の数値
- `latitude` (default: `138.989754`): 経度。`-180 <= latitude <= 180`の数値
- `zoom` (default: `12`): ズーム。`2 <= zoom <= 18`の整数
