---
title: "研究"
layout: "research"
description: "加藤誠の研究プロジェクト一覧．外部資金（JSTさきがけ・科研費など）に基づくプロジェクトごとに関連論文をまとめています．"
intro: >
  これまでに獲得した研究資金などに基づいて，研究プロジェクトごとに研究内容と関連論文をまとめています．
  データセット・ツールは「データ・ツール」ページで公開しています．
projects:
  - id: "client-side-ir"
    title: "クライアントサイド情報検索"
    period: "2025年 –"
    funding: "JSTさきがけ（令和7〜10年度）"
    link: "/project_csir/"
    image: "/images/csir_ja.png"
    summary: >
      本研究課題では，研究者のPC上で動作するクライアントサイドAIを用いて，研究活動や情報検索行動を常時モニタリングし，研究の発展に必要な情報を自律的に検索し提供する技術を開発する．これにより，プライバシーおよびセキュリティリスクを低減しつつ，研究者が意図して検索しようとする情報，意図して検索しないが有用な情報，研究の発展に資する情報を，適切なタイミングで研究者へ提供できるようにする．
  - id: "low-resource-ir"
    title: "低資源情報検索"
    period: "2023年 –"
    funding: "科研費 基盤研究(B)（令和5〜8年度）"
    summary: >
      「汎用検索モデルに基づく低資源下における情報検索システム構築技術の開発」として，大量の訓練データを用意できない低資源環境においても，新たなドメインやタスクに適応可能な汎用検索モデルに基づいて情報検索システムを構築する技術を開発しています．
  - id: "data-search"
    title: "データ検索"
    period: "2018年 –"
    funding: "JSTさきがけ（平成30〜33年度）"
    summary: >
      「データ検索エンジン」を構築し「世界中のオープンデータを整理し、世界中の人々がアクセスできて使えるようにする」ことを目指します。データ自体の分析によって索引を構築し、データの内容に関する問い合わせやデータの要約を実現することで、柔軟で効率的なオープンデータへのアクセスを可能にします。データ検索エンジンの実現により、オープンサイエンスと人々のデータに基づく科学的な意思決定を支援します。
    publications:
      - "**SIGIR 2021** Makoto P. Kato, Hiroaki Ohshima, Ying-Hsang Liu, Hsin-Liang Chen: A Test Collection for Ad-hoc Dataset Retrieval. In Proc. of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2021), pp. 2450-2456, 2021."
      - "**DSE 2022** Atsuki Maruta, Makoto P. Kato: Intent‑Aware Data Visualization Recommendation. Data Science and Engineering, 2022."
    resources:
      - "NTCIR-15 Data Searchタスク・NTCIR-16 Data Search 2タスク（タスクオーガナイザ）：データセット検索のための共有評価基盤"
  - id: "evidence-based-ir"
    title: "エビデンスに基づく情報検索"
    period: "2018年 – 2022年"
    funding: "科研費 基盤研究(B)（平成30〜34年度）"
    summary: >
      「数量データに基づくWeb情報の信頼性検証と高信頼情報の生成」として，テキストとデータの照合により，数量データに基づいてWeb情報の信頼性を検証し，信頼性の高い情報を生成する技術を研究しました．
    publications:
      - "**SIGIR 2019** Wiradee Imrattanatrai, Makoto P. Kato, Masatoshi Yoshikawa: Identifying Entity Properties from Text with Zero-shot Learning. In Proc. of the 42th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019), pp. 195-204, 2019."
    resources:
      - "**基調講演** ROCLING 2022: Matching Texts with Data for Evidence-based Information Retrieval"
  - id: "information-need-elicitation"
    title: "情報要求誘出"
    period: "2013年 – 2018年"
    funding: "科研費 若手研究(A)（平成26〜29年度）"
    summary: >
      ユーザからいかにして情報要求を引き出すかを研究しました．センサーや脳波，クリックなどからユーザがどのような情報を必要としているのかを，積極的にかつ効率的に推定する方法を提案しました．
    publications:
      - "**WSDM 2016** Makoto P. Kato, Katsumi Tanaka: To Suggest, or Not to Suggest for Queries with Diverse Intents: Optimizing Search Result Presentation. In Proc. of the 9th ACM International Conference on Web Search and Data Mining (WSDM 2016), pp. 133-142, 2016."
      - "**SIGIR 2014** Makoto P. Kato, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka: Investigating Users' Query Formulations for Cognitive Search Intents. In Proc. of the 37th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2014), pp. 577-586, 2014."
      - "**CIKM 2014** Shuya Ochiai, Makoto P. Kato, Katsumi Tanaka: Re-call and Re-cognition in Episode Re-retrieval: A User Study on News Re-finding a Fortnight Later. In Proc. of the 23th ACM International Conference on Information and Knowledge Management (CIKM2014), pp. 579-588, 2014."
      - "**IR Journal 2013** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: When Do People Use Query Suggestion? A Query Suggestion Log Analysis. Information Retrieval, 16(6), pp. 1-22, 2013."
    resources:
      - "[認知的適合性データセット・検索行動データ](/ja/data/)を公開しています"
  - id: "evaluation-behavior"
    title: "情報検索の評価とユーザ検索行動分析"
    period: "2011年 –"
    summary: >
      NTCIR評価ワークショップや理論的研究を通じて，情報アクセスシステムの評価手法の開発と，ユーザ検索行動の分析を行っています．INTENT・1CLICK・MobileClick・OpenLiveQ・Data SearchなどのNTCIRタスクをオーガナイズし，インターリービングに基づくオンライン評価のためのオープンソースツールを開発・公開しています．
    publications:
      - "**ECIR 2023** Kojiro Iizuka, Hajime Morita, Makoto P. Kato: Theoretical Analysis on the Efficiency of Interleaved Comparisons. In Proc. of the 45th European Conference on IR Research (ECIR 2023), pp. 459-473, 2023."
      - "**WebSci 2023** Yuki Yanagida, Makoto P. Kato, Yuka Kawada, Takehiro Yamamoto, Hiroaki Ohshima, Sumio Fujita: What Web Search Behaviors Lead to Online Purchase Satisfaction? In Proc. of the 15th ACM Web Science Conference 2023 (WebSci 2023), pp. 324-34, 2023."
      - "**WWW 2012** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: Structured Query Suggestion for Specialization and Parallel Movement: Effect on Search Behaviors. In Proc. of the 21th International World Wide Web Conference (WWW 2012), pp. 389-398, 2012."
      - "**NTCIR-9** Ruihua Song, Min Zhang, Tetsuya Sakai, Makoto P. Kato, Yiqun Liu, Miho Sugimoto, Qinglei Wang, Naoki Orii: Overview of the NTCIR-9 INTENT Task. NTCIR 2011, 2011."
    resources:
      - "[interleaving](https://github.com/mpkato/interleaving): インターリービングに基づくオンライン評価のためのPythonライブラリ"
      - "[openliveq](https://github.com/mpkato/openliveq)・[mobileclick-eval](https://github.com/mpkato/mobileclick-eval): NTCIRタスクの評価ツール"
  - id: "analogy-based-ir"
    title: "アナロジーに基づく情報検索"
    period: "2008年 – 2012年"
    funding: "日本学術振興会特別研究員 DC1（平成22〜24年度）／京都大学GCOE（平成21年度）／IPA未踏ユース（2008年度）"
    image: "/images/MapAnalogySearch.png"
    summary: >
      ユーザがすでに知っているものを手がかりに，よく知らない対象を検索する「例示・アナロジーに基づく検索」を研究しました．Web検索エンジンの索引を用いた関係検索「比例アナロジー検索」，「自分のよく知る地域だったらこの店」という探し方ができる「アナロジー飲食店検索」，「足して2で割ったようなミュージシャン」を検索できる混合検索「RhythMiXearch」，ソーシャルタグを用いて抽象語によるWeb画像検索を実現する「らしさ検索」などのシステムを開発しました．
    publications:
      - "**SIGIR 2012** Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka: Content-based Retrieval for Heterogeneous Domains: Domain Adaptation by Relative Aggregation Points. In Proc. of the 35th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2012), pp. 811-820, 2012."
      - "**CIKM 2009** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Query by Analogical Example: Relational Search Using Web Search Engine Indices. In Proc. of the 18th ACM International Conference on Information and Knowledge Management (CIKM 2009), pp. 27-36, 2009."
      - "**ISMIR 2009** Makoto P. Kato: RhythMiXearch: Searching for Unknown Music by Mixing Known Music. In Proc. of 10th International Society for Music Information Retrieval Conference (ISMIR 2009), pp. 477-482, 2009."
      - "**WISE 2008** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Can Social Tagging Improve Web Image Search? In Proc. of the 9th International Conference on Web Information Systems Engineering (WISE 2008), pp. 235-249, 2008. *(Kambayashi Best Paper Award)*"
    resources:
      - "[QAEデータセット・GORDデータセット](/ja/data/)を公開しています"
---
