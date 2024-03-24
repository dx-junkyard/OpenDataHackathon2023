# OpenData Bridge - オープンデータの加工と共有をシンプルに

## はじめに
OpenData Bridgeは、オープンデータの生成、加工、そして共有をサポートするツール群を提供します。
都知事杯DemoDayをご覧になったオープンデータの加工に関わる皆様、特に自治体職員の方々が直面しているオープンデータに関する課題を解決するために設計されています。


## コミュニティ参加のお誘い
dx-junkyardでは、技術共有やコラボレーションを通じて、互いに学び、支援し合うメンバーを募集しています。一緒に創造性と革新性に満ちた社会の実現に貢献しましょう。
[コミュニティ参加はこちらのフォームから](https://forms.gle/PVW4kYYh53SzbfdbA)


## OpenData Bridgeの主な機能
### 1. OpenData Lab: データ加工を、誰でも簡単に  [デモ動画](https://youtu.be/4bQnxkUSlBI)
想像してみてください。データ加工が、料理と同じくらい簡単にできる世界を。レシピさえあれば、誰でも美味しい料理を作ることができますよね。OpenData Bridge UIは、まさにその「レシピ」を提供します。そして、そのレシピは、プログラミングの知識がない方でも簡単に作成できるのです。

- AIの力で簡単プログラミング： 生成AIの支援により、プログラミングが苦手な方でも、簡単にデータ加工プログラムを作成できます。まるで、AIがあなたの料理の助手となり、必要なレシピを手早く用意してくれる感覚です。

- 成功レシピの保存と再利用： 一度成功したプロンプトやプログラムは、保存して再利用することができます。これは、自分だけのレシピブックを持つようなもの。お気に入りの料理をいつでも再現できる、そんな便利さを提供します。

- 情報の「補完」でより良い料理を： OpenData Bridge UIでは、補完用のAPIを通じて、データの不足部分を埋めることができます。例えば、施設の緯度経度や住所の一部、読み仮名など、欠けている情報を追加することで、あなたのデータセットをより充実させることが可能です。完璧を目指す代わりに、より正確で使いやすいデータへと進化させることを目指しましょう。この機能により、あなたのデータ加工プロジェクトは、より豊かな情報に基づいた、信頼性の高い成果物を生み出すことができます。



### 2. OpenData-Library：みんなで作る、データ加工のレシピ集  [詳細はこちら](https://github.com/dx-junkyard/OpenData-Library)
OpenData-Libraryは、地方自治体が提供するデータ（例えば、育児施設や避難所の情報など）を使いやすく加工するためのヒントやツールが詰まった宝箱です。この宝箱からは、誰でも自由に宝物（データ加工の方法やプログラム）を取り出して、自分のプロジェクトに活用することができます。

- AIの力を借りるヒント： 初めてオープンデータを加工する時に何をどうすればいいか迷ったら、ここにある「うまくいったプロンプト」と呼ばれる成功例を参考にしてみてください。これらは、AIを使ってデータを加工した時に有効だった手順やプログラムです。これにより、プログラミングが苦手な方でも簡単にデータ加工を始めることができます。

- 再利用しやすい： 一度うまくいった方法やプログラムは、保存して何度でも使えるようになっています。これにより、時間を節約しつつ、様々なデータに対して同じ加工を繰り返し適用することが可能になります。

- データ加工の流れを自動化： このリポジトリには、自治体のオープンデータサイトから情報を自動でダウンロードし、それを整理・加工して、使いやすい形（たとえばCSVファイル）に変換する一連の流れを構築するためのプログラムが含まれています。これにより、煩雑な手作業を減らし、より多くのデータを効率的に活用することができます。

- 共有と改善： OpenDataProcCodeLabは、みんなで一緒に作り上げていくプラットフォームです。一度成功した方法を共有することで、他の人もその成果を利用できるようになります。また、みんなで知恵を出し合い、より良い方法を見つけ出すことができるのです。



### 3. OpenData-Archive：地域のデータで新しい価値を創造するためのArchive   [詳細はこちら](https://github.com/dx-junkyard/OpenData-Archive)

- どんなデータがあるの？
  - OpenData-Archiveは、地方自治体が提供するさまざまなデータを集めた場所です。ここでは、育児施設、避難所、避難場所など、様々なカテゴリーに分けられたデータが整理されて公開される予定です。これらのデータは、[OpenData-Library](https://github.com/dx-junkyard/OpenData-Library)で事前に加工・整形されたもので、使いやすい形になります。

- 誰が使うの？
  - このライブラリは、データを基に新しいサービスを作りたい開発者や、データを分かりやすく可視化して情報を伝えたいデザイナーや研究者など、多くの人にとって有益なリソースです。例えば、地域の育児支援サービスを開発したい人が、育児施設のデータを探している場合、このライブラリから必要なデータを簡単に見つけることができます。

- なぜ便利なの？
  - OpenData-Libraryは、データを使って何かを始めたいときに、自分で一からデータを集めて整形する手間を省くことができる大きな助けになります。既に整形されているため、ダウンロードしてすぐに利用開始することが可能です。これにより、アイデアを形にするまでの時間を短縮し、より創造的な作業に集中できます。


### 4. OpenData-Bridge-pipeline：簡単に言えば、どこでもデータ加工工場を作れる仕組みです  [デモ動画](https://youtu.be/BJpaCAvKmTw),  [利用方法](https://github.com/dx-junkyard/OpenData-Bridge-pipeline)
- 「どこでも」の秘密 - Dockerコンテナ： OpenData Bridgeのpipelineは、Dockerコンテナを使用しています。これは、特定のソフトウェアを「箱」に入れてどこでも開けられるようにする技術です。この「箱」があれば、パソコンの種類や場所に関わらず、必要な環境でデータの加工ができます。自宅のPCでも、会社のPCでも、全く同じ条件で作業が可能になります。

- 「瞬時に手元に」の魔法 - ライブラリからのパイプライン定義： OpenData Bridgeでは、さまざまなデータ加工方法がライブラリに共有されています。これを使うと、世界中の誰かが考えたデータ加工のプロセスを、ボタン一つで自分の手元に「呼び出す」ことができます。これにより、新しいデータ加工方法を探したり、試したりする時間が大幅に節約できます。

- 「自由に実験」できる自在性： 自分の手元に持ってきたデータ加工プロセスは、まるでレゴブロックのように自由に変更が可能です。例えば、ある部分を少し変えてみたい、もっと効率的な方法があるか試してみたいと思った時、簡単に修正して実験することができます。これにより、自分だけのカスタマイズされたデータ加工プロセスを開発することが可能になります。


## 都知事杯オープンデータ・ハッカソン2023DemoDay発表資料
- [2024/03/16 資料](20240316.pdf)
- [2024/03/16 動画](https://www.youtube.com/watch?v=GrIohSqZYEY&t=5723s)

## 連絡先
OpenData Bridgeやデモ動画に関するご質問、その他のお問い合わせはこちらからお願いいたします。
[https://www.dx-junkyard.com/](https://www.dx-junkyard.com/)

![メール](em_add.png)


