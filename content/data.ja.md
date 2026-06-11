---
title: "データ・ツール"
---

## ツール

- [interleaving](https://github.com/mpkato/interleaving): インターリービングを行うためのPythonライブラリ．観測されたユーザクリックに基づき，複数のランカーを比較できます．
- [openliveq](https://github.com/mpkato/openliveq): NTCIR OpenLiveQのためのPythonパッケージ
- [mobileclick-eval](https://github.com/mpkato/mobileclick-eval): NTCIR-12 MobileClick-2の評価スクリプト

## データセット

### Optimizing Search Result Presentation 実験データ
デスクトップ・モバイル検索タスクで記録された256名のユーザの検索行動データ，NTCIR INTENT-1およびINTENT-2トピックに対する20名のユーザによるインテント投票，NTCIR INTENT-1およびINTENT-2テストコレクションを対象としたランキング学習用特徴量を公開しています．

#### ダウンロード
- [Search behavior data](https://www.dropbox.com/s/bs6abx0kfntdcwl/search_behavior_data.tar.gz)
- [Intent votes](https://www.dropbox.com/s/jfobsd6oqsdblyw/intent_votes.tar.gz)
- [Learning-to-rank features](https://www.dropbox.com/s/om2dthrihfsrr3r/learning_to_rank.tar.gz)

#### 関連論文
- Makoto P. Kato, Katsumi Tanaka (2016) To Suggest, or Not to Suggest for Queries with Diverse Intents: Optimizing Search Result Presentation, In Proc. of the 9th ACM International Conference on Web Search and Data Mining (WSDM2016)

### 会話型適合性フィードバックのためのテストコレクション
会話型適合性フィードバック（CRF）システムを評価するための2つのテストコレクションを公開しています．

#### ダウンロード
- [Celebrity Test Collection](https://www.dropbox.com/s/l7ndf3ut8mr9l7l/celebrity.tar.gz)
- [Restaurant Test Collection](https://www.dropbox.com/s/glh4ehgjagjtcp6/restaurant.tar.gz)

### 認知的適合性データセット
認知的適合性に関する適合性判定を含むデータセットです．分かりやすさ，網羅性，主観性／客観性，具体性／抽象性を考慮した検索システムの評価に利用できます．トピックの例として「分かりやすいブラックホール」「主観的なMacbook Pro」などがあります．

#### ダウンロード
- [Cognitive Relevance Dataset](https://www.dropbox.com/s/vebpo8j6lyqr101/CognitiveRelevanceDataset.zip)

#### 関連論文
- Makoto P. Kato, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka (2014) Investigating Users' Query Formulations for Cognitive Search Intents, In Proc. of the 37th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2014)

### 地理オブジェクト検索データセット (GORD)
異種ドメインにおけるコンテンツベース検索を評価するために作成された，検索インテント，飲食店オブジェクト，適合性判定を含むデータセットです．コンテンツベース検索だけでなく，状況に応じた飲食店検索にも利用できます．

#### ダウンロード
- [GORD Ver. 1.0](https://www.dropbox.com/s/0fxjtfimmc81mft/GORD.v1.0.zip)

#### 関連論文
- Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka (2012) Content-based Retrieval for Heterogeneous Domains: Domain Adaptation by Relative Aggregation Points, In Proc. of the 35th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2012)

### Query by Analogical Example (QAE) データセット
特定の関係が存在するxとyのペアの集合を含むデータセットです．例えば，x=Appleとy=iPodの間には「MP3（プレイヤー）」という関係があります．x1，y1，x2を入力し，x1とy1の関係と同じ関係を持つy2をシステムが返すかどうかを調べることで，関係検索システムを評価できます．

#### ダウンロード
- [QAE-dataset](https://www.dropbox.com/s/jl68d0pd85l04eh/QAE-dataset.zip)

#### 関連論文
- Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka (2009) Query by analogical example: relational search using web search engine indices, In Proc. of the 18th ACM conference on Information and knowledge management (CIKM2009)
