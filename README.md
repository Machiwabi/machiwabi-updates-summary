# MachiwabiDocs

マチワビは、待ち侘びる時間を価値にするWeb3アプリケーションです。待ち侘びた時間は、リワードと交換できます。


##  5th Wave Latest Updates

- En
  - 1.The first of the Proof of Concept (from the start of the waiting period to the end of the event) has been completed, including the exchange of rewards for NFTs.
    - The implementation and verification of the point contract have begun (MatiwabiToken721 and MissionToken1155).
  - 2.Testing of integration between Metame (UE5) and Machiwabi.
  - 3.Implementation of the Treasure Mission, where finding a code within the metaverse space increases the point increase rate.
- Ja
  - 1.PoC第1週目(待ち時間開始〜イベント終了)完了
    - リワードとのNFTの引き換え実施
  - 2.ポイントコントラクトの実装と検証を開始(MatiwabiToken７２１,MissionToken1155)
  - 3.Metame(UE5)とマチワビの連携テスト
    - トレジャーミッションの実装　メタバース空間内部でコードを見つけるとポイント上昇率が上がる仕組みの実装

### 1,PoC [1st PoC Implementation: Tokyo Dome Event 06/03-06/23

- En
  - We offered an experience where fans could stake points while eagerly waiting for the pro wrestling event. During this wait, fans could increase their staking rate by tipping their favorite talents or tweeting about the event.
- Ja
  - PoCでは、マチワビにユーザーが継続的に来訪・アクションすることがわかり、一定の価値を証明できました。「マチワビに参加するユーザーがいる」「課金する」「SNSでのアクションをする」という学びを得たことは、チームにとって大きい収穫でした。

### 2.Implemented PointContracts (MatiwabiToken721,MissionToken1155)

https://github.com/Machiwabi/machiwabi-contracts

- En
  - An extension of ERC721 called "MatiwabiToken721" is designed to start when Machiwabi is initiated. It includes a function that derives points based on the block number difference.
  - "MissionToken1155," earned upon completing missions, is an extension of ERC1155. In collaboration with MatiwabiToken721, it can increase the point gain of MatiwabiToken721. The more you acquire, the more points MatiwabiToken721 gains.
  - Deployment and operational verification have begun on Manta Pacific Sepolia Testnet and Sepolia TestNet.
- Ja
  - マチワビを開始するともらえる「MatiwabiToken721」なるERC721の拡張を設計。ブロック番号の差分に応じてポイントを導出する関数を備えています。
  - ミッションを達成するともらえる「MissonToken1155」。これはERC1155の拡張で、MatiwabiToken721と連携して、Matiwabi721のポイント増加量を増やすことができるようになります。取得すればするほど、MatiwabiToken721のポイントが増えるという仕組みになっています。
  - MantaPacificSepoliaTestnetおよびSepoliaTestNetにデプロイを行い動作検証を開始しています。

#### About MatiwabiToken721 / MissionToken1155
<img width="2249" alt="001" src="https://github.com/Machiwabi/machiwabi-docs/assets/1862066/96b62be2-bc94-493d-90f5-e80789b18253">

#### Integration of Experiences and On-Chain Technology
<img width="2249" alt="002" src="https://github.com/Machiwabi/machiwabi-docs/assets/1862066/c36e8986-4675-4902-9ba2-42366ed98184">

#### Contract List

|ContractName|Network|BlockExplorer|
|:--|:--|:--|
|MatiwabiToken721|manta-sepolia-testnet|https://pacific-explorer.sepolia-testnet.manta.network/address/0x497b1B27540e4205B7315DEdF1B062CA4f5345cD|
|MatiwabiToken721|sepolia|https://sepolia.etherscan.io/address/0xE1C4FFf0B8FA1e078d253F43B8AC26aaA806d65b#code
|MissionToken1155|manta-sepolia-testnet|https://pacific-explorer.sepolia-testnet.manta.network/address/0xf472fed0404F907dB77d3052f95ad75B317f3e07|
|MissionToken1155|sepolia|https://sepolia.etherscan.io/address/0xaf3E61dDa90956085060dce183dA0d928610D9B2|

### 3.In Metaverse, we implemented the Treasure Mission, where finding a code within the metaverse space increases the point increase rate.

<img width="2249" alt="003" src="https://github.com/Machiwabi/machiwabi-docs/assets/1862066/b887002d-7885-4725-9b7c-f483495d6854">

- En
  - I propose a draft of a mission called "Treasure Mission." In this mission, participants explore a virtual space during the waiting time before an event. When they discover a hidden treasure (a string of characters), their point increase rate improves.
  - This system can be easily set up in a virtual space by embedding a URL, which encourages exploration and revisitation.

- Ja
  -  「トレジャーミッション」なるミッションの素案を提案。イベント開催前の待ち侘び時間にてバーチャル空間を回遊し、トレジャー隠された文字列を発見するとポイント増加率が向上するというもの。
  - URLを埋め込むだけでバーチャル空間に簡単に仕掛けることができ、回遊と再訪率を促すという仕組みを実現します。


#### Movie　｜MetaMe with Matiwabi 

https://www.youtube.com/watch?v=iATaj2PmMys
[![alt設定](http://img.youtube.com/vi/iATaj2PmMys/0.jpg)](https://www.youtube.com/watch?v=iATaj2PmMys)
