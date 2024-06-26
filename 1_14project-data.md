<link href="../default.css" rel="stylesheet"/>
<script src="../navall.js" defer></script>
<script src="nav.js" defer></script>
<script src="../default.js" defer></script>

# 参考資料: プロジェクト課題のデータについて

三種類のデータの検索名と検索結果のデータ項目をここに掲載します．

## NHK の番組表

### 検索キー

|検索キー| 検索キーの説明 | 取りうる値|備考 |
|-------|-------------|---------|---------|
|service|チャンネル| g1, e1 | g1はNHK総合1，e1はEテレ1|
|genre|ジャンル | 取りうる値は次のとおり | |

ジャンルの取りうる値と意味:
- 0000 ... ニュース・報道
- 0100 ... スポーツ
- 0205 ... 情報・ワイドショー
- 0300 ... ドラマ
- 0409 ... 音楽
- 0502 ... バラエティ
- 0600 ... 映画
- 0700 ... アニメ
- 0800 ... ドキュメンタリー・教養
- 0903 ... 劇場・公演
- 1000 ... 趣味・教育
- 1100 ... 福祉

### 検索結果のデータ項目

|項目名| 項目の説明|
|-----|---------|
|start_time|番組開始時刻|
|end_time|番組終了時刻|
|service.name|チャンネル|
|title|番組名|
|subtitle|番組サブタイトル|
|content|番組説明文|
|act|出演者|

## グルメ情報

### 検索キー
検索キーは `genre` （ジャンル）1つだけです．

genre の取りうる値:
- G001  ... 居酒屋
- G002  ... ダイニングバー・バル
- G003  ... 創作料理
- G004  ... 和食
- G005  ... 洋食
- G006  ... イタリアン・フレンチ
- G007  ... 中華
- G008  ... 焼肉・ホルモン
- G009  ... アジア・エスニック料理
- G010  ... 各国料理
- G011  ... カラオケ・パーティ
- G012  ... バー・カクテル
- G013  ... ラーメン
- G014  ... カフェ・スイーツ
- G015  ... その他グルメ
- G016  ... お好み焼き・もんじゃ
- G017  ... 韓国料理

### 検索結果のデータ項目

|項目名| 項目の説明|
|-----|---------|
|access|アクセス情報|
|address|住所|
|budget.name|予算|
|catch|キャッチコピー|
|genre.name|ジャンル|
|name|店舗名|
|open|営業日時|
|station_name|最寄駅|
|sub_genre.name|サブジャンルの名前|

## 世界の天気

### 検索キー
検索キーは `id` （都市のID）1つだけです．

都市のIDの取りうる値:
- 360630  ... Cairo   カイロ  （エジプト）
- 524901  ... Moscow  モスクワ        （ロシア）
- 993800  ... Johannesburg    ヨハネスブルク  （南アフリカ）
- 1816670 ... Beijing 北京    （中華人民共和国）
- 1850147 ... Tokyo   東京    （日本）
- 1880252 ... Singapore       シンガポール
- 2147714 ... Sydney  シドニー        （オーストラリア）
- 2643743 ... London  ロンドン        （イギリス）
- 2968815 ... Paris   パリ    （フランス）
- 3451189 ... Rio de Janeiro  リオデジャネイロ        （ブラジル）
- 5128581 ... New York        ニューヨーク    （アメリカ合衆国）
- 5368361 ... Los Angeles     ロサンゼルス    （アメリカ合衆国）

### 検索結果のデータ項目

|項目名|項目の説明|
|-----|--------|
|coord.lon|緯度|
|coord.lat|経度|
|weather[0].description|天気|
|main.temp_min|最低気温|
|main.temp_max|最高気温|
|main.humidity|湿度|
|wind.speed|風速|
|wind.deg|風向|
|name|都市名|

