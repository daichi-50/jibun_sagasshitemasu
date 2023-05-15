■ サービス概要
自分のやりたいこと得意なことが分からない。だから、身近な人たちから意見がもらいたい人が、
自己開示のハードルを下げることができるようにする
トレーニングサービス『自分探してます』です

■　ユーザーが抱える課題
自分は何がやりたいのか分からない。だから具体的なアドバイスをもらいたいが人に聞けない。

■　課題に対する仮説
- 他の人に意見をもらうことに消極的になっている
  1. どのように人に相談したらいいのか分からない
  2. 自分のことを話すのが恥ずかしい

■　解決方法
- ユーモア（ネタ的な要素）で解決する。他の人への情報をユーモアを交えて投稿する
  - フォーマットを用意して相談しやすくする
  - 笑いに変えることで相談しやすくする

■　メインのターゲットユーザー
20〜30代前半の方、やりたいこと得意なことが明確でない人

■　実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
- 自己理解を深めたいユーザー
    - LPに訪れたユーザーが会員登録ができる
       - ユーザーがLPを閲覧できる
       - ユーザーが、パスワード、名前、メールアドレスから会員登録できる
       - ユーザーがゲストログインできる
- 会員登録、ゲストログインしたユーザー
    - 会員登録、ゲストログインしたユーザーがコンテンツを投稿できる
       - 名前と知りたい自分の構成要素を入力できる
       - それらを失くした場所をgoogle mapでピン留めできる
       - TwitterとLINEに共有することができる
    - 会員登録したユーザー
       - 会員登録したユーザーは投稿にコメントができる
       - 会員登録したユーザーが投稿にいいねができる
    - 会員登録、ゲストログインしたユーザーはマイページに行くことができる
       - 自分の過去の投稿を閲覧できる
       - 他のユーザーからもらった意見をまとめることができる
- 管理ユーザー
    - 会員登録ユーザーの検索、一覧、詳細、編集
    - ゲストログインユーザーの検索、一覧、詳細、編集
    - 管理ユーザーの一覧、詳細、作成、編集、削除

■　なぜこのサービスを作りたいのか？
自分を探すのは恥ずかしいと感じる人が多いのではないでしょうか？
それを笑いに変えることができたらいいなと思います！
あと、思いついた時に楽しくなったからです！！！

■　スケジュール

企画〜技術調査：5/22〆切
README〜ER図作成：６/1 〆切
メイン機能実装：6/1 - 7/1
β版をRUNTEQ内リリース（MVP）：7/1〆切
本番リリース：８月

■　技術選定
- Rails7
- postgresql
- JavaScript
- Bootstrap
- heroku
- google map API
- Twitter API
- LINE API

■画面遷移図

Figma: https://www.figma.com/file/KQ2aJP5SwLXdLOzcgdv0sC/%E7%84%A1%E9%A1%8C?type=design&node-id=27%3A130&t=wJTYj95A54ph0wH6-1

### READMEに記載した機能
- [ ] ユーザー登録機能
- [ ] ログイン機能
- [ ] パスワード変更機能
- [ ] メールアドレス変更機能
- [ ] 記事投稿機能（画像投稿含む）
- [ ] 記事閲覧機能（未ログインでも閲覧可）
- [ ] 記事編集機能
- [ ] 記事削除機能
- [ ] コメント投稿機能
- [ ] コメント閲覧機能（未ログインでも閲覧可）
- [ ] コメント編集機能
- [ ] コメント削除機能
- [ ] イイね機能
- [ ] イイね解除機能
- [ ] google mapに座標追加
- [ ] Twitterに投稿機能
- [ ] LINEに投稿機能

### 未ログインでも閲覧or利用できるページ
以下の項目はちゃんと未ログインでも閲覧or利用できる画面遷移になっているか？
- [ ] 記事投稿機能（画像投稿含む）
- [ ] コメント閲覧機能（未ログインでも閲覧可）

### メールアドレス・パスワード変更確認項目
直に変更できるものではなく、一旦メールなどを介して専用のページで変更する画面遷移になっているか？
- [ ] メールアドレス
- [ ] パスワード

### 想定URL
[こちら](https://xd.adobe.com/view/53d16b6b-bcdf-479b-4e6a-a67539af96c5-25e0/grid/)と同様にURLを記載している場合は違和感がないものになっているか？（必須ではありません）
- [ ] 特に記載していない or 特に違和感を感じなかった