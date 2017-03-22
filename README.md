# 日本で Erlang/OTP や Elixir を利用している会社一覧

- 日本国内版
- Pull-Request ください
    - 信頼性を担保するために中の人のみでお願いします
    - 後ろに付け足していってください
    - コミットログは適当で英語でも日本語でも良いです
- カテゴリー分けは後回し
- 求人情報歓迎
- まずは適当に書いて貰えると嬉しいです
- Erlang/OTP と Elixir 両方利用している方は Elixir に書いてください

こうした方が良いとかは Twitter で @voluntas か GitHub Isuues へお気軽にご連絡ください。

## テンプレート

```
### [会社名](会社 URL)

- 箇条書きで Erlang のプロダクション利用について好きなだけ

会社のアピールや求人を好きなだけ
```

## Erlang/OTP

### [株式会社時雨堂](https://shiguredo.jp/)

- Erlang/OTP 利用製品
    - [MQTT Broker Akane](http://akane.shiguredo.jp)
    - [WebRTC SFU Sora](http://sora.shiguredo.jp)
- rebar3, elvis 利用

フルスクラッチで開発した WebRTC SFU を中心に Erlang/OTP のコンサルティングなどいろいろやっています。

### [株式会社VOYAGE GROUP](http://voyagegroup.com/)

- Erlang/OTP 利用サービス
  - [fluct SSP](http://corp.fluct.jp/)
  
広告オークションシステムのコンポーネントをErlangで実装しています。

### [Kpnetworks株式会社](http://www.kpnetworks.jp/)

- Erlang/OTP 利用製品
  - IoTプラットフォーム, IoTゲートウェイ機器

ファクトリーデータを収集、処理する通信ミドルウェアに Erlang/OTP を利用しています。

### [株式会社gumi](https://gu3.co.jp)

- Erlang/OTP 利用
  - 認証・課金共通基盤
  - リアルタイムメッセージングサーバー
  - 簡易AIサーバー

モバイルゲームのバックエンドで Erlang/OTP を利用しています。 

### [株式会社ドワンゴ](http://dwango.co.jp)

- Erlang/OTP 利用サービス
  - ニコニコ動画, ニコニコ生放送のコンテンツ配信システム
  - その他(秘密)

社内で生息してる bot などのツールで Elixir を使っている事例もありますが、プロダクトレベルでは使っておりません。

また、エンジニアも積極的に[募集しております](http://nico.ms/job/966)。

### [ユミルリンク株式会社](https://www.ymir.co.jp)

- Erlang 利用サービス
  - Cuenote FC 一斉配信サービスの独自MTA・メール文書生成エンジン部分
  - Cuenote SRS メールリレー製品（MTA・Web管理画面）
  - Cuenote アンケートサービスのシステム全般

Erlang/OTPのOTP部分（gen_*等）は利用せず、使いやすく改良した自社ライブラリを使っています。
nifも独自C++ライブラリでラップし、ライブラリ中で多用しています。
事業拡大のため[エンジニア絶賛募集中](https://recruit.ymir.co.jp/)です。

### [SORABITO株式会社](https://www.sorabito.com/) (SORABITO Inc.)

- Erlang/OTP 利用
  - リアルタイムオークションシステムの基盤

重機や建機のオンラインマーケットプレイス [ALLSTOCKER](https://allstocker.com/) にて、同サイトがサービスする ALLSTOCKER Auction のバックエンドで Erlang/OTP を利用しています。 

SORABITO では利用技術に明確な制限はなく、[さまざまなエンジニアを募集](https://www.sorabito.com/recruit/)しています。

## Elixir

### [クックパッド株式会社](http://cookpad.com/) (Cookpad Inc.)

- Elixir利用社内アプリ
  - (モバイル)端末管理Webアプリ

社内の端末管理Webアプリや、(モバイルアプリ向け)テストツールの一部にElixirを利用しています。

### [株式会社ミクシィ](https://mixi.co.jp/)

- Elixir 利用サービス
  - [XFLAG STATION（エクステ）](https://station.xflag.com/)
  - Phoenix framework 利用

新規事業にて積極的に[採用](http://xflag.com/recruit/career/engineer.html)も行っています。


### [株式会社アカツキ](http://aktsk.jp/)

- [ライブエクスペリエンス事業(LX事業)](http://aktsk.jp/service/liveexperience.html) にて、近日リリース予定のウェブアプリケーションに Elixir & Phoenix を利用しています。

### [株式会社ドリコム](http://www.drecom.co.jp/)

- Elixir 利用サービス
  - [DreeVee(動画広告ネットワーク)](http://www.drecom.co.jp/pr/2015/07/20150730.php)
  - メディアコンテンツ
  - 一部社内ツール

動画広告アドネットワークの配信APIや、一部メディアコンテンツにElixirを利用しています。

ただいまエンジニアを[絶賛募集中](http://www.drecom.co.jp/recruit/)です。

### [Supership株式会社](https://supership.jp/)

- Elixir 利用サービス
  - Sunnychatのサーバーサイドで一部利用
    - [iOS](https://itunes.apple.com/jp/app/sunnychat-chaohappinachatto/id1134862745?mt=8)
    - [Android](https://play.google.com/store/apps/details?id=space.amigo&hl=ja)

[エンジニア採用行っております。](https://recruit.supership.jp/job/)

### [株式会社エス・エム・エス](http://www.bm-sms.co.jp/)

- Elixir 利用サービス
  - ヘルスケア事業部で会員基盤や病院検索など、メディア以外の機能に Phoenix を利用しています。

### [株式会社ACCESS](https://jp.access-company.com/)

- Elixir製 Application Platform 開発・運用(**OSS化準備中!**)
  - [Cowboy](https://github.com/ninenines/cowboy)ベースの独自プラットフォーム
  - 複数のWebアプリケーションを統一環境でホスト
  - CI機構内包、Hot Code Upgradeによる無停止デプロイ、アプリケーション間でのコード共有・プロセスレベル通信、プロセスプールによる流量制限等々実現
  - 複数商用案件稼働中

組込系Webブラウザで長年の実績を持つ会社ですが、最近はWebサービス開発を拡大中。Elixirは社内的に絶賛推進中です。

エンジニアは随時募集中です。[メール](mailto:empinfo_career_o-gr@access-company.com)にてご連絡下さい。
