# OpenDataHackathon2023

## 私達はOpenDataの「見つからない」と「形式がバラバラで使いにくい」という問題を解消し、データを作る人と使う人の架け橋を提供します。

## 着目した課題
現状、オープンデータの活用には様々な課題があります。例えば、
- 目的のデータを探すことが難しい
- 自治体ごとに項目、項目名、並びが異なる
- 処理の妨げになるような注釈の書き方がなされている


他にも様々な問題がありますが、こうした問題はデータを価値ある利用先（サービス）に結びつけることができていないため改善サイクルが回らず、データ整備を体系立てて進めるための仕組みと文化が育たなかったことが原因として考えられます。

## サービス概要
私達の**OpenData Bridge**は、オープンデータの作成・整備が促進されるような文化を育む土壌を仕組みとして提供することで、小さな改善サイクルが数多く回る状態を目指します。

### OpenData Bridgeの主な機能
- データ収集と整形を支援する**Tools**
- データ収集と整形方法を**レシピ**としてみんなで**共有するLibrary**
- データ収集と整形のレシピを入れて**整形済みデータを自動で生成するPipeline**


### OpenData Bridge全体像
![OpenData Bridge全体像](whole_image.png)


### 詳細説明
- OpenData Bridge Tools
  - データ検索を支援します
    - [OpenData検索 Webアプリ](https://opendata-bridge.dx-junkyard.com)
    - ChatGPTプラグイン([JapanOpen Data](https://github.com/FooQoo/japan-opendata-chatgpt-plugin/blob/develop/docs/usage.md))
  - データ整形を支援します
    - [DataNorm](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm/blob/main/README.md)の提供
- Library
  - データの収集・整形レシピを共有し、データ整備できる人を増やします
    - [データ収集レシピ](https://github.com/dx-junkyard/OpenData-Library/tree/main/resources_configs)
    - [データ整形レシピ](https://github.com/dx-junkyard/OpenData-Library/tree/main/converters)
  - 整備したデータを共有し、一つでも多くのサービスで利用できる状態にします
- Pipeline
  - データ収集、整形のレシピを組み込んでデータ整備を自動化します
    - [手元でPipeline実行](https://github.com/dx-junkyard/OpenData-Bridge-DataNorm#b-pipeline%E3%81%A7%E8%87%AA%E5%8B%95%E5%8C%96)
    - [github actionsでPipelineを定期実行](https://github.com/dx-junkyard/OpenData-Bridge-DataPipeline)


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
