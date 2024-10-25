# DustHunters

[DustHunters](https://dust-hunters.com)

[![Image from Gyazo](https://i.gyazo.com/591e5ec27e538e9a393c32942521845b.jpg)](https://gyazo.com/591e5ec27e538e9a393c32942521845b)

## アプリ概要

**本アプリは日々の掃除にゲーム要素を加え、掃除を毎日楽しく行える『お掃除支援アプリ』となっています。**

- 本アプリは「掃除 × 狩」のアプリとなっています。
- 5 分間掃除クエストに挑戦しモンスターを討伐することで、HR(ハンターランク)を上昇させることができます。
- 他にも、モンスター図鑑、活動履歴、掃除場所のグラフなど掃除した記録を残すことができます。

## 開発背景

私は子供の頃から掃除を習慣化することが苦手でした。毎年年末の大掃除に「毎日少しづつ片付ければ、もっと楽なのにな〜」と思いつつ、毎年掃除を習慣化出来ていませんでした。
そんな掃除を後回しにしてしまう自分自身の経験から生まれました。夏休みの宿題を最後の日にまとめてやるタイプの人間で、継続的な習慣化が難しいと考えてました。
そんな私でも 1 日 5 分間だけなら可能だと考え作成しました。そして、更なる習慣化を実現するために私の好きなゲームの`モンスターハンター`のゲーム要素を付け加えることにしました。
これにより、掃除が苦手な私でも「毎日 5 分」、「好きなゲーム」と掃除への難易度が緩和させられるだろうと思い、この Web アプリを開発しました。

## 主要機能

- ログイン機能(Google 認証)
- クエスト機能
- X シェア機能
- ギルドカード機能
- プロフィール編集機能

### 🐉 クエスト機能

クエスト一覧ページから、任意の掃除場所のクエストを選択します。<br>
選択すると戦闘画面へ移り、`戦闘開始`ボタンを押下すると 5 分間のカウントダウンが始まります。この間に選択した場所の掃除をします<br>
カウントダウンが終了すると`攻撃する`ボタンが出現し、モンスターに攻撃することが可能になります。<br>

| クエスト一覧                                                                                                                        | 戦闘画面                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [![Image from Gyazo](https://i.gyazo.com/a7a6e62e22207cf95dd7800eceea1952.jpg)](https://gyazo.com/a7a6e62e22207cf95dd7800eceea1952) | [![Image from Gyazo](https://i.gyazo.com/b3d9722803f545d3f3911e0319d18e4f.jpg)](https://gyazo.com/b3d9722803f545d3f3911e0319d18e4f) |

### 🌏X シェア機能

`Xに共有する`ボタンを押下すると新規ウィンドウが立ち上がり、X のポスト画面に遷移し、討伐したモンスターを X に共有できます！

| クエスト結果                                                                                                                        | X シャア                                                                                                                            |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [![Image from Gyazo](https://i.gyazo.com/ca835a1501bed7f0f89fdbdb0984d58a.jpg)](https://gyazo.com/ca835a1501bed7f0f89fdbdb0984d58a) | [![Image from Gyazo](https://i.gyazo.com/b4b5448f0ba9686512ee0f844e457d85.png)](https://gyazo.com/b4b5448f0ba9686512ee0f844e457d85) |

### 🪪 ギルドカード機能

【📕 図鑑】討伐したモンスターが登録され、討伐数が閲覧できます。<br>
【⏰ 活動履歴】1 日 1 クエスト完了することでスタンプが押されます。あとから、見返すことも可能です！<br>
【🧹 掃除場所】今までどこを何回掃除したかをグラフで確認することができます！<br>

| 図鑑                                                                                                                                | 活動履歴                                                                                                                            | 掃除場所グラフ                                                                                                                      |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| [![Image from Gyazo](https://i.gyazo.com/6e9a61c86dc1374b9fccb27dddad2e45.jpg)](https://gyazo.com/6e9a61c86dc1374b9fccb27dddad2e45) | [![Image from Gyazo](https://i.gyazo.com/df8d5b1aca8127084fd9f3fc704dce61.jpg)](https://gyazo.com/df8d5b1aca8127084fd9f3fc704dce61) | [![Image from Gyazo](https://i.gyazo.com/deb5ffe716bd16f2a08af494eaed5c12.jpg)](https://gyazo.com/deb5ffe716bd16f2a08af494eaed5c12) |

### 👤 プロフィール機能

プロフィールページから「名前」「性別」を編集することが可能です！<br>
性別を変更すると画面左下のアバターが変化します。<br>
余談ですが、ユーザーからはその他のアバターが気に入っていただけています!<br>

[![Image from Gyazo](https://i.gyazo.com/51dc81a446505d382d5c934b248a5c85.jpg)](https://gyazo.com/51dc81a446505d382d5c934b248a5c85)
| 男性 | 女性 | その他 |
| ---- | ---- | ---- |
| [![Image from Gyazo](https://i.gyazo.com/c299260957256f04a3c8504b5c560313.jpg)](https://gyazo.com/c299260957256f04a3c8504b5c560313) | [![Image from Gyazo](https://i.gyazo.com/a66b762403587960159ec33454a257f4.jpg)](https://gyazo.com/a66b762403587960159ec33454a257f4) | [![Image from Gyazo](https://i.gyazo.com/411bf70cb0e3e4e9249cc2dc9530fb3d.jpg)](https://gyazo.com/411bf70cb0e3e4e9249cc2dc9530fb3d) |

## 使用技術

| カテゴリ       | 技術                                                                                                    | 選定理由                                                                                  |
| -------------- | ------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| フロントエンド | Next.js / TypeScript                                                                                    | SPA(シングルページアプリケーション)の開発に最適だと判断したため                           |
| バックエンド   | Ruby on Rails (API モード)                                                                              | 開発スピードが担保できるため                                                              |
| データベース   | PostgreSQL                                                                                              | 複雑なクエリや ACID トランザクションの処理が強力なため                                    |
| CSS / UI       | Tailwind CSS / MaterialUI                                                                               | 開発時のスタイリング作業の効率化のため / コンポーネントの豊富さとカスタマイズ性の高さから |
| 認証           | omniauth-google-oauth2 / jwt                                                                            | 認証フローカスタムしたかったため                                                          |
| 開発環境       | Docker                                                                                                  | 一貫性のある開発環境を簡単に構築できるため                                                |
| インフラ       | Vercel / Render.com                                                                                     | Next.js との互換性が高いため / 導入コストが低く、開発スピードを担保できるため             |
| コード品質管理 | ESLint / Prettier / Rubocop                                                                             | コードの品質及び、フォーマットを統一するため                                              |
| その他         | swr / jwt-decode / date-fns / NoSleep.js / react-chartjs-2 / chartjs-plugin-datalabels / @types/gtag.js | 別途後述します                                                                            |

### 技術選定理由詳細

#### 【Next.js について】

**① ユーザービリティ向上のため**

- 掃除アプリのロード時間が長いと、ユーザーが本来行うはずの作業が億劫になることを防ぐため、SPA（シングルページアプリケーション）の Next.js を採用しました。
- SPA の特性を活かし、ページ遷移をスムーズにすることでユーザーがストレスなく操作できると考え、ユーザビリティ向上のため。

**② フロントエンドスキル向上のため**

- カリキュラムで学習した基礎的な JavaScript の知識を活かし、実践的なフロントエンド技術をさらに深めたいと考えたため。

**③ ページルーティング、SSR,SSG を容易に実装できるため**

- React とは異なり、ライブラリを使ってルーティングを手動で設定せずともページルーティングが行えるため。
- ディレクトリの配置次第でルーティングの設定が決まるのでメンテナンスのしやすいと考えたため。
- React とは異なり、SSR（サーバーサイドレンダリング）や SSG（静的サイト生成）を容易に実装でき、それにより SEO 対策や初回ロードの高速化が可能となり、検索エンジンからの評価向上やユーザー体験の向上につながると考えたため。

#### 【TypeScript について】

**① 型による安全性の確保とバグの予防**

- 静的型付けを提供するため、型に基づいて変数や関数の扱いを厳密に管理でき、型の不一致などによるバグを予防できると考えたため。

**② エディタサポートによる開発効率の向上**

- エディタと連携してコード補完や型推論、リファクタリングが強力にサポートされていて、エディタ上でエラーや警告が即時に表示されることで、開発効率が向上すると考えたため。

#### 【Ruby on Rails について】

**① 開発、制作速度の担保**

- バックエンドの言語の中で`Ruby on Rails`が 1 番使い慣れていて、一定の開発速度を担保できるため。
- 使い慣れている言語、フレームワークであるため工数の見積もりや実装イメージがつきやすいと考えたため。

**② ドキュメントが豊富なため**

- Ruby をもとに作られているので、日本語のドキュメントが豊富に揃っているため。

#### 【認証について】

**①omniauth-google-oauth2**

- Google の OAuth 2.0 サービスを利用して認証を行うため

**②jwt**

- JWT をエンコードおよびデコードし、トークンベースの認証や情報交換に使用したいため。

**③ なぜ、認証ライブラリを使用しなかったのか**

- 今回はログイン認証時に GuildCard レコードを自動作成する処理を組み込みたかったため。
- Device の場合、認証フローが決まっていて変更する際にオーバーライドしないといけなかったため。
- Sorcery は内部認証に優れていますが、Google などの外部認証には適していないと考えたため。
- 認証フローを独自で実装し、その流れを掴むことで、認証の仕組みをより深く学習したかったため。

#### 【インフラについて】

**①Vercel**

- Vercel は Next.js を開発した企業であり、Next.js の機能（SSR、SSG、ISR など）を最適化してホスティングできるため、パフォーマンスと開発効率が向上すると考えたため。
- 導入が簡単で、Git リポジトリとの連携により自動デプロイが可能であるため。
- 個人開発の場合、無料で使用できるのでコスト面を考慮したため。

**②Render.com**

- GitHub と連携することで自動デプロイできるため。
- 導入コストが簡単で、使い慣れているため開発コストの担保のため。

#### 【なぜ、バックとフロントを分断したのか】

**① 開発効率と役割分担の向上**

- フロントエンドとバックエンドを分離することで、それぞれの領域を独立して開発でき、効率的な役割分担が可能になり、お互いの責務が明確になると考えたため。

**② パフォーマンスの最適化**

- Rails API モードをバックエンドとして活用し、Next.js をフロントエンドで使用することで、クライアントとサーバー間のデータやレスポンスを効率化できると考えたため。

**③ 自己学習のため**

- より実務近い形で学習してみたかったため。
- API の設計と実装に関する知識を深めたかったため。

#### 【その他について】

**①swr**

- fetch 時に使用。データの自動キャッシュ管理とリアルタイムな再取得を簡単に実現でき、開発効率とパフォーマンスが向上すると考えたため。

**②date-fns**

- 活動履歴に使用。軽量で使いやすい日付操作ライブラリで、日付処理ができるため。

**③NoSleep.js**

- 戦闘開始ページのカウントダウンの際に使用。モバイル版だと一定時間を経過してしまい、スリープ状態になってしまうのでスリープ対策のため。

**④eact-chartjs-2 / chartjs-plugin-datalabels**
掃除場所グラフに使用。

- eact-chartjs-2 : グラフの描写に使用
- chartjs-plugin-datalabels : グラフないに数字を表示させるために使用

**⑤@types/gtag.js**

- Google Analytics のトラッキングを型安全に行うため、TypeScript 環境で gtag.js をスムーズに導入でき、ユーザー行動の計測が正確に行えるため

## ER 図

[ER 図 URL](https://dbdiagram.io/d/66c6a5aca346f9518cbd1faf)

[![Image from Gyazo](https://i.gyazo.com/e1a3dd5ebdccda3b395870eda1fe1a6c.png)](https://gyazo.com/e1a3dd5ebdccda3b395870eda1fe1a6c)

## 画面遷移図

[画面遷移図 URL](<https://www.figma.com/board/sAzTNXPLSa3DvkeypbFgwv/Dsut-Hunters(%E3%83%80%E3%82%B9%E3%83%88%E3%83%8F%E3%83%B3%E3%82%BF%E3%83%BC)?node-id=0-1&node-type=canvas&t=yzAnpj7YKX4KZuzx-0>)

[![Image from Gyazo](https://i.gyazo.com/7a42a436fdd38ed0fe87f6f7d34eb70e.jpg)](https://gyazo.com/7a42a436fdd38ed0fe87f6f7d34eb70e)
