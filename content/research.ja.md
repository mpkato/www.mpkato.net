---
title: "研究"
layout: "research"
description: "加藤誠の研究プロジェクト一覧．外部資金（JSTさきがけ・科研費など）に基づくプロジェクトごとに関連論文をまとめています．"
intro: >
  これまでに獲得した研究資金などに基づいて，研究プロジェクトごとに研究内容と関連論文をまとめています．継続中のテーマと終了したテーマを緩やかに分けています．
  データセット・ツールは「データ・ツール」ページで公開しています．図はそれぞれの研究の考え方を表した概念図です．
projects:
  - id: "client-side-ir"
    title: "クライアントサイド情報検索"
    status: "ongoing"
    period: "2025年 –"
    funding: "JSTさきがけ（令和7〜10年度）"
    link: "/project_csir/"
    image: "/images/projects/client-side-ir.svg"
    summary: >
      本研究課題では，研究者のPC上で動作するクライアントサイドAIを用いて，研究活動や情報検索行動を常時モニタリングし，研究の発展に必要な情報を自律的に検索し提供する技術を開発する．これにより，プライバシーおよびセキュリティリスクを低減しつつ，研究者が意図して検索しようとする情報，意図して検索しないが有用な情報，研究の発展に資する情報を，適切なタイミングで研究者へ提供できるようにする．
    publications:
      - "**SIGIR 2026** Koji Nishikawa, Makoto P. Kato: H-MAPS: Hierarchical Memory-Augmented Proactive Search Assistant for Scientific Literature. To appear in Proc. of ACM SIGIR 2026."
  - id: "low-resource-ir"
    title: "低資源情報検索"
    status: "ongoing"
    period: "2023年 –"
    funding: "科研費 基盤研究(B)（令和5〜8年度）"
    image: "/images/projects/low-resource-ir.svg"
    summary: >
      「汎用検索モデルに基づく低資源下における情報検索システム構築技術の開発」として，大量の訓練データを用意できない低資源環境においても，新たなドメインやタスクに適応可能な汎用検索モデルに基づいて情報検索システムを構築する技術を開発しています．
    publications:
      - "**SIGIR 2025** Kenya Abe, Kunihiro Takeoka, Makoto P. Kato, Masafumi Oyamada: LLM-based Query Expansion Fails for Unfamiliar and Ambiguous Queries. In Proc. of ACM SIGIR 2025, pp. 3035–3039."
      - "**SIGIR-AP 2025** Yuto Nakachi, Makoto P. Kato: Impact of LLM-Modified Queries and Documents in Training Data on Neural Retrieval Models. In Proc. of ACM SIGIR-AP 2025, pp. 364–373."
      - "**ECIR 2025** Haruki Fujimaki, Makoto P. Kato: Investigating the Performance of Dense Retrievers for Queries with Numerical Conditions. In Proc. of ECIR 2025, pp. 210–218."
      - "**IEICE 2025** Huu-Long Pham, Ryota Mibayashi, Takehiro Yamamoto, Makoto P. Kato, Yusuke Yamamoto, Yoshiyuki Shoji, Hiroaki Ohshima: Pre-trained BERT Model Retrieval: Inference-Based No-Learning Approach using k-Nearest Neighbour Algorithm. IEICE Trans. Inf. Syst. 108(8), pp. 872–882, 2025."
      - "**WISE 2024** Takumi Ito, Atsuki Maruta, Makoto P. Kato, Sumio Fujita: PR-Rank: A Parameter Regression Approach for Learning-to-Rank Model Adaptation Without Target Domain Data. In Proc. of WISE 2024, pp. 3–18."
      - "**CIKM 2024** Kota Usuha, Makoto P. Kato, Sumio Fujita: Over-penalization for Extra Information in Neural IR Models. In Proc. of ACM CIKM 2024, pp. 4096–4100."
  - id: "ir-evaluation"
    title: "情報検索の評価"
    status: "ongoing"
    period: "2011年 –"
    image: "/images/projects/evaluation-behavior.svg"
    summary: >
      NTCIR評価ワークショップや理論的研究を通じて，情報アクセスシステムの評価手法を開発しています．インターリービング・マルチリービングに基づくオンライン評価を含み，INTENT・1CLICK・MobileClick・OpenLiveQ・Data SearchなどのNTCIRタスクをオーガナイズしてきました．
    publications:
      - "**ECIR 2023** Kojiro Iizuka, Hajime Morita, Makoto P. Kato: Theoretical Analysis on the Efficiency of Interleaved Comparisons. In Proc. of ECIR 2023, pp. 459–473."
      - "**ICTIR 2021** Kojiro Iizuka, Yoshifumi Seki, Makoto P. Kato: Decomposition and Interleaving for Variance Reduction of Post-click Metrics. In Proc. of ACM ICTIR 2021, pp. 221–230."
      - "**CIKM 2020** Makoto P. Kato, Akiomi Nishida, Tomohiro Manabe, Sumio Fujita, Takehiro Yamamoto: What Rankers Can be Statistically Distinguished in Multileaved Comparisons? In Proc. of ACM CIKM 2020, pp. 2081–2084."
      - "**CIKM 2018** Makoto P. Kato, Tomohiro Manabe, Sumio Fujita, Akiomi Nishida, Takehiro Yamamoto: Challenges of Multileaved Comparison in Practice: Lessons from NTCIR-13. In Proc. of ACM CIKM 2018, pp. 1515–1518."
      - "**SIGIR 2017** Tomohiro Manabe, Akiomi Nishida, Makoto P. Kato, Takehiro Yamamoto, Sumio Fujita: A Comparative Live Evaluation of Multileaving Methods on a Commercial cQA Search. In Proc. of ACM SIGIR 2017, pp. 949–952."
    resources:
      - "[interleaving](https://github.com/mpkato/interleaving): インターリービングに基づくオンライン評価のためのPythonライブラリ"
      - "[openliveq](https://github.com/mpkato/openliveq)・[mobileclick-eval](https://github.com/mpkato/mobileclick-eval): NTCIRタスクの評価ツール"
  - id: "data-search"
    title: "データ検索"
    status: "past"
    period: "2018年 – 2025年"
    funding: "JSTさきがけ（平成30〜33年度）／科研費 基盤研究(B)（平成30〜34年度）"
    image: "/images/projects/data-search.svg"
    summary: >
      「データ検索エンジン」を構築し，世界中のオープンデータを整理して誰もがアクセス・活用できるようにすることを目指しました．データ自体の分析によって索引を構築し，柔軟で効率的なオープンデータへのアクセスを可能にします．あわせて「エビデンスに基づく情報検索」として，テキストとデータ・知識ベースを照合し，情報の信頼性を検証したりエンティティを属性に基づいてランキングしたりする技術も扱い，オープンサイエンスとデータに基づく意思決定を支援しました．
    publications:
      - "**HCII 2025** Wiradee Imrattanatrai, Makoto P. Kato, Ken Fukuda: Enhancing User Understanding of Entity Relationships with Knowledge Graphs: A Dataset for Multi-entity Relationship Explanation. In Proc. of HCI International 2025, pp. 197–205."
      - "**DSE 2022** Atsuki Maruta, Makoto P. Kato: Intent-Aware Data Visualization Recommendation. Data Science and Engineering 7(4), pp. 301–315, 2022."
      - "**NTCIR-16** Makoto P. Kato, Hiroaki Ohshima, Ying-Hsang Liu, Hsin-Liang Chen, Yu Nakano: Overview of the NTCIR-16 Data Search 2 Task. In Proc. of NTCIR 2022."
      - "**SIGIR 2021** Makoto P. Kato, Hiroaki Ohshima, Ying-Hsang Liu, Hsin-liang Oliver Chen: A Test Collection for Ad-hoc Dataset Retrieval. In Proc. of ACM SIGIR 2021, pp. 2450–2456."
      - "**WISE 2021** Atsuki Maruta, Makoto P. Kato: Intent-Aware Visualization Recommendation for Tabular Data. In Proc. of WISE 2021, pp. 252–266."
      - "**ASIS&T 2021** Ying-Hsang Liu, Hsin-liang Oliver Chen, Makoto P. Kato, Mingfang Wu, Kathleen Gregory: Data Discovery and Reuse in Data Service Practices: A Global Perspective. In Proc. of ASIS&T Annual Meeting 2021, pp. 610–612."
      - "**ASIS&T 2020** Ying-Hsang Liu, Hsin-Liang Chen, Makoto P. Kato, Mingfang Wu, Isto Huvila: Supporting open research data practice through data curation and discovery: A global perspective. In Proc. of ASIS&T Annual Meeting 2020."
      - "**ECIR 2020** Makoto P. Kato, Wiradee Imrattanatrai, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka: Context-Guided Learning to Rank Entities. In Proc. of ECIR 2020, pp. 83–96."
      - "**SIGIR 2019** Wiradee Imrattanatrai, Makoto P. Kato, Masatoshi Yoshikawa: Identifying Entity Properties from Text with Zero-shot Learning. In Proc. of ACM SIGIR 2019, pp. 195–204."
      - "**IEICE 2018** Wiradee Imrattanatrai, Makoto P. Kato, Katsumi Tanaka, Masatoshi Yoshikawa: Entity Ranking for Queries with Modifiers Based on Knowledge Bases and Web Search Results. IEICE Trans. Inf. Syst. 101-D(9), pp. 2279–2290, 2018."
      - "**WI 2017** Wiradee Imrattanatrai, Makoto P. Kato, Katsumi Tanaka: Entity search by leveraging attributive terms in sentential queries over RDF data. In Proc. of IEEE/WIC/ACM WI 2017, pp. 769–776."
    resources:
      - "NTCIR-15 Data Searchタスク・NTCIR-16 Data Search 2タスク（タスクオーガナイザ）：データセット検索のための共有評価基盤"
      - "**基調講演** ROCLING 2022: Matching Texts with Data for Evidence-based Information Retrieval"
  - id: "information-need-elicitation"
    title: "情報要求誘出とユーザ検索行動分析"
    status: "past"
    period: "2012年 – 2023年"
    funding: "科研費 若手研究(A)（平成26〜29年度）"
    image: "/images/projects/information-need-elicitation.svg"
    summary: >
      ユーザからいかにして情報要求を引き出すかを研究しました．センサーや脳波，クリックなどからユーザがどのような情報を必要としているのかを積極的かつ効率的に推定する方法を提案するとともに，クエリ提案からオンライン購買行動まで，幅広いユーザ検索行動の分析も行いました．
    publications:
      - "**WebSci 2023** Yuki Yanagida, Makoto P. Kato, Yuka Kawada, Takehiro Yamamoto, Hiroaki Ohshima, Sumio Fujita: What Web Search Behaviors Lead to Online Purchase Satisfaction? In Proc. of ACM WebSci 2023, pp. 324–334."
      - "**WSDM 2016** Makoto P. Kato, Katsumi Tanaka: To Suggest, or Not to Suggest for Queries with Diverse Intents: Optimizing Search Result Presentation. In Proc. of ACM WSDM 2016, pp. 133–142."
      - "**SIGIR 2014** Makoto P. Kato, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka: Investigating users' query formulations for cognitive search intents. In Proc. of ACM SIGIR 2014, pp. 577–586."
      - "**CIKM 2014** Shuya Ochiai, Makoto P. Kato, Katsumi Tanaka: Re-call and Re-cognition in Episode Re-retrieval: A User Study on News Re-finding a Fortnight Later. In Proc. of ACM CIKM 2014, pp. 579–588."
      - "**WSDM 2013** Shinya Tanaka, Adam Jatowt, Makoto P. Kato, Katsumi Tanaka: Estimating content concreteness for finding comprehensible documents. In Proc. of ACM WSDM 2013, pp. 475–484."
      - "**IR Journal 2013** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: When do people use query suggestion? A query suggestion log analysis. Information Retrieval 16(6), pp. 725–746, 2013."
      - "**CHI 2013** Makoto P. Kato, Ryen W. White, Jaime Teevan, Susan T. Dumais: Clarifications and question specificity in synchronous social Q&A. In Proc. of ACM CHI 2013, pp. 913–918."
      - "**WWW 2012** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: Structured query suggestion for specialization and parallel movement: effect on search behaviors. In Proc. of The Web Conference (WWW) 2012, pp. 389–398."
    resources:
      - "[認知的適合性データセット・検索行動データ](/ja/data/)を公開しています"
  - id: "analogy-based-ir"
    title: "アナロジーに基づく情報検索"
    status: "past"
    period: "2008年 – 2012年"
    funding: "日本学術振興会特別研究員 DC1（平成22〜24年度）／京都大学GCOE（平成21年度）／IPA未踏ユース（2008年度）"
    image: "/images/projects/analogy-based-ir.svg"
    summary: >
      ユーザがすでに知っているものを手がかりに，よく知らない対象を検索する「例示・アナロジーに基づく検索」を研究しました．Web検索エンジンの索引を用いた関係検索「比例アナロジー検索」，「自分のよく知る地域だったらこの店」という探し方ができる「アナロジー飲食店検索」，「足して2で割ったようなミュージシャン」を検索できる混合検索「RhythMiXearch」，ソーシャルタグを用いて抽象語によるWeb画像検索を実現する「らしさ検索」などのシステムを開発しました．
    publications:
      - "**SIGIR 2012** Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka: Content-based retrieval for heterogeneous domains: domain adaptation by relative aggregation points. In Proc. of ACM SIGIR 2012, pp. 811–820."
      - "**ICME 2012** Yuki Sugiyama, Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka: Relative Relevance Feedback in Image Retrieval. In Proc. of IEEE ICME 2012, pp. 272–277."
      - "**CIKM 2010** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Search as if you were in your home town: geographic search by regional context and dynamic feature-space selection. In Proc. of ACM CIKM 2010, pp. 1541–1544."
      - "**ICUIMC 2010** Makoto P. Kato, Satoshi Oyama, Hiroaki Ohshima, Katsumi Tanaka: Query by example for geographic entity search with implicit negative feedback. In Proc. of ICUIMC 2010, p. 45."
      - "**CIKM 2009** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Query by analogical example: relational search using web search engine indices. In Proc. of ACM CIKM 2009, pp. 27–36."
      - "**ISMIR 2009** Makoto P. Kato: RhythMiXearch: Searching for Unknown Music by Mixing Known Music. In Proc. of ISMIR 2009, pp. 477–482."
      - "**WISE 2008** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Can Social Tagging Improve Web Image Search? In Proc. of WISE 2008, pp. 235–249. *(Kambayashi Best Paper Award)*"
    resources:
      - "[QAEデータセット・GORDデータセット](/ja/data/)を公開しています"
---
