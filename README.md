# 職務経歴書

## 基本情報

#### Profile

|key|value|
|---|-----|
|Name|保立 由理 (Hotate Yuri))|
|Age|28 (1990/06/15)|
|Education|立教大学観光学部観光学科)|
|address|神奈川県横浜市港北区新横浜|
|from|静岡県|

#### SNS・Webサービス

|service|account|
|---|-----|
|GitHub|[yuri-swift](https://github.com/yuri-swift)|
|Twitter|[@yuri_htt](https://twitter.com/yuri_htt)|
|hatena|[yuri's Tech Note](https://yuri-hotate.hatenablog.com/)|


## 職務経歴

### 2016/5 - : 株式会社Link Sports

職務: Web、モバイルアプリケーションエンジニア

#### チームスポーツマネジメントアプリTeamHub開発

- iOS(Swift)アプリの実装
- iOS、Android(React Native)アプリの実装
  - テストの導入
  - CIの導入
  - リブランディング(Good Design賞受賞)
- Webアプリ(Vue)の実装
  - Reactへの移行


### 2014/09 - 2016/04: 株式会社BTM

職務: フロントエンドエンジニア

#### Webアプリ(フロント)の実装

- Webアプリ開発(HTML,CSS)
  - [大人の休日倶楽部](http://www.jreast.co.jp/otona/)
- 某銀行Webアプリ開発(Java)


## 個人開発
### ダンス動画閲覧アプリ Dancers(Swift)
2017/12-2018/1

大学時代にダンスサークルに所属していたことからダンス動画をよく見るので、自分でダンス動画にタグなどをつけて管理できるダンス動画閲覧アプリを作りました。

Youtubeの動画を引用したサービス設計をしていましたが、開発途中でYoutubeの動画を引用するのはCC BYライセンスが付与されていない動画に関しては法律的にグレーであるということを知り(弁護士.comで相談しました)ストアに公開することなく終了しました。

この開発にはRailsのエンジニアと共同で作成し、もう一人のメンバーには動画の取得とカテゴリ登録を行う管理画面を作ってもらい、管理画面で登録されたアプリがDancersで閲覧できるようにしました。

しかし、動画を私たちの方で１つ１つ確認、カテゴリを振り分ける作業などが必要になり、運用にコストがかかるという点でいけてないサービスになってしまった点は大きな反省点となりました。

https://qiita.com/yuri_RN/items/007f926ae6c11dec8a6f

### お酒記録アプリ SAKE BOARD(JavaScript)
酔っ払った状態でも簡単に飲んだお酒を記録できるよう、音声でお酒を検査し記録できるアプリを作成しました。

今回は一人で作りきりたかったため、バックエンドはすべてFirebaseでまかないました。

algoliaというサービスを使用して全文検索に対応させる工夫をしており、お酒の名前のような固有名詞はどうしても音声検索で検索しにくいという点を解決しました。

Androidのみストアに公開してあります。(iOSは実機を持っていなかったため、検証できず未公開です)

React Native / Firestore / Firebase Authentication / algolia

https://play.google.com/store/apps/details?id=com.voicealcoholsearcher
