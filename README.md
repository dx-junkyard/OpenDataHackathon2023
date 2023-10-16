# OpenDataHackathon2023

## 私達はOpenDataの「見つからない」と「形式がバラバラで使いにくい」という問題を解消し、データを作る人と使う人の架け橋を提供します。

## 着目した課題
- 目的のデータを探すことが難しい
- 自治体ごとに項目、項目名、並びが異なる
- 独自の注釈がファイル中にあり、処理の妨げになっている
- 表記ゆれ


## サービス概要
OpenData Bridgeは以下３つの機能を提供することでオープンデータをサービスで使える状態にします。
- データの収集・整形を行うTool群([検索plugin](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md),[整形](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm))
- 収集・整形レシピの共有するための[Library](https://github.com/dx-junkyard/OpenData-Library)
- 収集・整形を自動化するためのpipeline([1](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm#b-pipeline%E3%81%A7%E8%87%AA%E5%8B%95%E5%8C%96), [2 github actions](https://github.com/dx-junkyard/OpenData-Bridge-DataPipeline))

### OpenData Bridge全体像
![OpenData Bridge全体像](whole_image.png)


### 詳細説明
私達は作成されたオープンデータがサービスで活用できるよう、以下の機能を提供します。
- OpenData Bridge Tools
  - OpenData検索ChatGPTプラグイン([JapanOpen Data](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md))の提供
  - OpenData検索Webアプリ：プラグインとテンプレートを簡単に使えるアプリの提供（使用料の制限により利用先を限定中）
  - [OpenData修正＆整形](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm/blob/main/README.md)の提供

- Library
  - データの収集・整形プロセスと結果を共有し、オープンデータ利用を加速する
  - 集めてきたデータを目的に沿った形で修正・整形するための定義

- Pipeline
  - データ収集、整形作業を自動化


OpenDataの「見つからない」と「使いにくい」を解消するため、以下を提供します。
- OpenData検索ChatGPTプラグイン([JapanOpen Data](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md))の提供
- プラグインを有効活用するための[テンプレート](https://github.com/dx-junkyard/OpenDataHackathon2023/tree/main/prompt_template)の提供

## ハッカソンでの発表
- First Stage 2023-09-10
  - [発表資料](OpenData-Bridge_ODH23_0910.pdf)、[YouTube](https://youtu.be/0QoSDb9AM9o)
- Final Stage 2023-10-22
  - [発表資料](OpenData-Bridge_ODH23_1022.pdf)

## デモ動画
- [Webアプリ](https://youtu.be/JeJejE0zTpw) : OpenData検索プラグインとテンプレートを統合し、誰でも簡単にオープンデータが見つかる(利用先制限中)
- [プラグイン&テンプレート](https://youtu.be/yfqMH_vYTvU)：ChatGPT上で[JapanOpenData](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md) pluginとノウハウの詰まった[テンプレート](https://github.com/dx-junkyard/OpenDataHackathon2023/tree/main/prompt_template)を利用し、地図上に可視化するまでのデモ
- [バラバラのデータを統合](https://youtu.be/GS9HADN9fh8) : バラバラのcsv項目を指定したデータの項目に合わせて統合します。ChatGPTで入力データに合わせた変換定義を作成し、Pythonのプログラムでデータ変換と結合を行います。

## 連携サービス
[都知事杯OpenDataHackathon2023](https://odhackathon.metro.tokyo.lg.jp/) において下記の参加チームの開発サービス向けに、使用されるデータの整備や、データ検索＆整形など本プロジェクトのツール群を使ったサポートを実施しております。
- 発表ID 7  「シェアード法令(SLO)」 【調整中】根っこから！パブリックを動かすルールを学び合うプラットフォーム
- 発表ID 40 「こそだてっく」  【連携済】[子育て困り事解決ポータル（デモサイト）](https://preview.studio.site/live/V5a7JbynqR)
- 発表ID 41 「マイナセーフティ」 【調整中】災害時に近くの人と助け合える仕組み

データ検索、整形などでお手伝いできそうなサービスがあればご連絡ください。


## FAQ
[FAQ Page](Sep10-2023_FAQ.md)

## リンク
- [JapanOpenData プラグイン](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md)
- [JapanOpenData用プロンプトテンプレート集](https://github.com/dx-junkyard/OpenDataHackathon2023/tree/main/prompt_template)
- [データ変換の仕組み](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm)

## 連絡先
[https://www.dx-junkyard.com/](https://www.dx-junkyard.com/)  
![メール](em_add.png)
