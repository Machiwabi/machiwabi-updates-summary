# MachiwabiDocs

マチワビは、待ち侘びる時間を価値にするWeb3アプリケーションです。待ち侘びた時間は、リワードと交換できます。


#  5th Wave Latest Updates

### Updates

- PoC第1週目(待ち時間開始〜イベント終了)完了
　　　- リワードとのNFTの引き換え実施
- ポイントコントラクトの実装と検証を開始(MatiwabiToken７２１,MissionToken1155)
- Metame(UE5)とマチワビの連携テスト
    - トレジャーミッションの実装　メタバース空間内部でコードを見つけるとポイント上昇率が上がる仕組みの実装

### PoC [1st PoC Implementation: Tokyo Dome Event 06/03-06/23

- We offered an experience where fans could stake points while eagerly waiting for the pro wrestling event. During this wait, fans could increase their staking rate by tipping their favorite talents or tweeting about the event.

- PoCでは、マチワビにユーザーが継続的に来訪・アクションすることがわかり、一定の価値を証明できました。「マチワビに参加するユーザーがいる」「課金する」「SNSでのアクションをする」という学びを得たことは、チームにとって大きい収穫でした。


### ポイントコントラクトの実装と検証を開始

- An extension of ERC721 called "MatiwabiToken721" is designed to start when Machiwabi is initiated. It includes a function that derives points based on the block number difference.
- "MissionToken1155," earned upon completing missions, is an extension of ERC1155. In collaboration with MatiwabiToken721, it can increase the point gain of MatiwabiToken721. The more you acquire, the more points MatiwabiToken721 gains.
- Deployment and operational verification have begun on Manta Pacific Sepolia Testnet and Sepolia TestNet.

- マチワビを開始するともらえる「MatiwabiToken721」なるERC721の拡張を設計。ブロック番号の差分に応じてポイントを導出する関数を備えています。
- ミッションを達成するともらえる「MissonToken1155」。これはERC1155の拡張で、MatiwabiToken721と連携して、Matiwabi721のポイント増加量を増やすことができるようになります。取得すればするほど、MatiwabiToken721のポイントが増えるという仕組みになっています。
- MantaPacificSepoliaTestnetおよびSepoliaTestNetにデプロイを行い動作検証を開始しています。

#### MatiwabiToken721 / MissionToken1155
<img width="2249" alt="001" src="https://github.com/Machiwabi/machiwabi-docs/assets/1862066/96b62be2-bc94-493d-90f5-e80789b18253">

#### Integration of Experiences and On-Chain Technology
<img width="2249" alt="002" src="https://github.com/Machiwabi/machiwabi-docs/assets/1862066/c36e8986-4675-4902-9ba2-42366ed98184">

### バーチャルイベント連携



# バーチャルイベント連携

コード外のドキュメントを整備してアップロードしていくリポジトリです。

## v0.2 ワイヤーフレーム兼ミニマムデザイン版

<img src="https://github.com/Machiwabi/machiwabi-docs/blob/main/min-design.png" >

#### Figma

- [Figma で見る：全体図](https://www.figma.com/design/Ov9DF41vGmjLwqRmWB0w92/machiwabi_wireframe?node-id=0%3A1&t=kKb9ujT9FZbAGPft-1)
- [Figma で見る：モック版にて](https://www.figma.com/proto/Ov9DF41vGmjLwqRmWB0w92/machiwabi_wireframe?node-id=91-13748&t=kKb9ujT9FZbAGPft-0&scaling=scale-down&page-id=0%3A1)

#### v0.2 経緯

- [現在のプロトタイプ](https://stg.app.machiwabi.xyz/waitings/dPgbsW-e_HRSSdfcEvqOuA)を用いてユーザーヒアリングを実施。
- その後チームで議論し、ワイヤーフレームに落とし込み
  - UI パーツのチグハグさの解消
  - 獲得したリワードが見られる場所がない問題の解消
  - ブースターの種別を増やす
  - デイリーミッションなどリテンションを高める要素の追加
  - 相対的にどのくらいの自分の気持ちがあるのかをランキングで表示する
  - 登録フローの整理
  - ユーザー間のコミュニケーションを促進する要素の追加
