# Streetcar Timetable

Streetcar Timetableは、函館の市電の時刻表や路線のデータを、csvやyamlで提供するものです。

## 提供する交通機関
* 市電(函館市)

## ファイル構成
* README.md -> Busearchの説明です。  
* stops.yml -> 停留所名が書いてあります。(日本語, 英語)
* stops.csv -> stops.ymlのcsv版です。
* days.yml -> 曜日が書いてあります。(日本語, 英語)
* days.csv -> days.ymlのcsv版です。
* directions.yml -> 系統と行き先が書いていきます。(日本語, 英語)
* directions.csv -> directions.ymlのcsv版です。
* LICENSE -> ライセンスが書いてあります。  
* holiday -> 休日の時刻表  
  - yunokawa-hakodate.yml -> 湯の川〜谷地頭・函館どつく  
  - hakodate-yunokawa.yml -> 谷地頭・函館どつく〜湯の川  
* weekday -> 平日の時刻表  
  - yunokawa-hakodate.yml -> 湯の川〜谷地頭・函館どつく  
  - hakodate-yunokawa.yml -> 谷地頭・函館どつく〜湯の川

## stops.csv stops.yml のファイルについて
1. 停留所の番号
2. 停留所名(日本語)
3. 停留所名(英語)
4. 停留所の経度
5. 停留所の緯度

## ライセンス
Copyright (c) 2014 [Ryo Sugimoto](https://github.com/sugryo)

[BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause)
