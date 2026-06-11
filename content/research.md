---
title: "Research"
layout: "research"
description: "Research projects by Makoto P. Kato, organized by funded research programs: client-side information retrieval, data search, IR evaluation, and more."
intro: >
  My research projects, organized by the research programs that have funded
  them. Each project lists its related publications; datasets and tools are
  available on the Data & Tools page.
projects:
  - id: "client-side-ir"
    title: "Client-side Information Retrieval"
    period: "2025 –"
    funding: "JST PRESTO (FY2025–FY2028)"
    link: "/project_csir/"
    image: "/images/csir_en.png"
    summary: >
      In this research project, we develop technologies that employ
      client-side AI running on researchers' PCs to continuously monitor
      research activities and information-seeking behaviors, autonomously
      retrieving and providing information necessary for advancing research.
      This approach reduces privacy and security risks while enabling the
      timely delivery of information that researchers intend to search for,
      information they did not explicitly intend to search for but is still
      useful, and information that contributes to the progress of their
      research.
  - id: "low-resource-ir"
    title: "Low-Resource Information Retrieval"
    period: "2023 –"
    funding: "JSPS KAKENHI (B) (FY2023–FY2026)"
    summary: >
      This project develops technologies for building information retrieval
      systems in low-resource settings, based on generalist retrieval models
      that can be adapted to new domains and tasks without large amounts of
      training data.
  - id: "data-search"
    title: "Data Search"
    period: "2018 –"
    funding: "JST PRESTO (FY2018–FY2021)"
    summary: >
      This research aims to develop a data search engine for organizing the
      world's open data and making it universally accessible and useful. The
      data search engine provides flexible and efficient access to open data
      by realizing queries on implications from data and data summarization
      through an index built by data analysis. We encourage open science and
      data-driven scientific decision making of the general public by
      establishing the data search engine.
    publications:
      - "**SIGIR 2021** Makoto P. Kato, Hiroaki Ohshima, Ying-Hsang Liu, Hsin-Liang Chen: A Test Collection for Ad-hoc Dataset Retrieval. In Proc. of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2021), pp. 2450-2456, 2021."
      - "**DSE 2022** Atsuki Maruta, Makoto P. Kato: Intent‑Aware Data Visualization Recommendation. Data Science and Engineering, 2022."
    resources:
      - "NTCIR-15 Data Search and NTCIR-16 Data Search 2 tasks (task organizer): shared evaluation infrastructure for ad-hoc dataset retrieval"
  - id: "evidence-based-ir"
    title: "Evidence-based Information Retrieval"
    period: "2018 – 2022"
    funding: "JSPS KAKENHI (B) (FY2018–FY2022)"
    summary: >
      Toward evidence-based information retrieval, this project studied how to
      verify the credibility of Web information based on quantitative data and
      how to generate highly credible information, by matching natural
      language texts with data.
    publications:
      - "**SIGIR 2019** Wiradee Imrattanatrai, Makoto P. Kato, Masatoshi Yoshikawa: Identifying Entity Properties from Text with Zero-shot Learning. In Proc. of the 42th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2019), pp. 195-204, 2019."
    resources:
      - "**Keynote** ROCLING 2022: Matching Texts with Data for Evidence-based Information Retrieval"
  - id: "information-need-elicitation"
    title: "Information Need Elicitation"
    period: "2013 – 2018"
    funding: "JSPS KAKENHI Young Scientists (A) (FY2014–FY2017)"
    summary: >
      We studied how to elicit information needs from users. Sensors, brain
      signals, and search behaviors such as clicks were used to estimate
      desired information actively and effectively.
    publications:
      - "**WSDM 2016** Makoto P. Kato, Katsumi Tanaka: To Suggest, or Not to Suggest for Queries with Diverse Intents: Optimizing Search Result Presentation. In Proc. of the 9th ACM International Conference on Web Search and Data Mining (WSDM 2016), pp. 133-142, 2016."
      - "**SIGIR 2014** Makoto P. Kato, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka: Investigating Users' Query Formulations for Cognitive Search Intents. In Proc. of the 37th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2014), pp. 577-586, 2014."
      - "**CIKM 2014** Shuya Ochiai, Makoto P. Kato, Katsumi Tanaka: Re-call and Re-cognition in Episode Re-retrieval: A User Study on News Re-finding a Fortnight Later. In Proc. of the 23th ACM International Conference on Information and Knowledge Management (CIKM2014), pp. 579-588, 2014."
      - "**IR Journal 2013** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: When Do People Use Query Suggestion? A Query Suggestion Log Analysis. Information Retrieval, 16(6), pp. 1-22, 2013."
    resources:
      - "[Cognitive Relevance Dataset and search behavior data](/data/) used in these studies"
  - id: "evaluation-behavior"
    title: "IR Evaluation and Search Behavior Analysis"
    period: "2011 –"
    summary: >
      Through the NTCIR evaluation campaigns and theoretical studies, we
      develop evaluation methodologies for information access systems and
      analyze user search behavior. We have organized NTCIR tasks such as
      INTENT, 1CLICK, MobileClick, OpenLiveQ, and Data Search, and developed
      open-source tools for online evaluation based on interleaving.
    publications:
      - "**ECIR 2023** Kojiro Iizuka, Hajime Morita, Makoto P. Kato: Theoretical Analysis on the Efficiency of Interleaved Comparisons. In Proc. of the 45th European Conference on IR Research (ECIR 2023), pp. 459-473, 2023."
      - "**WebSci 2023** Yuki Yanagida, Makoto P. Kato, Yuka Kawada, Takehiro Yamamoto, Hiroaki Ohshima, Sumio Fujita: What Web Search Behaviors Lead to Online Purchase Satisfaction? In Proc. of the 15th ACM Web Science Conference 2023 (WebSci 2023), pp. 324-34, 2023."
      - "**WWW 2012** Makoto P. Kato, Tetsuya Sakai, Katsumi Tanaka: Structured Query Suggestion for Specialization and Parallel Movement: Effect on Search Behaviors. In Proc. of the 21th International World Wide Web Conference (WWW 2012), pp. 389-398, 2012."
      - "**NTCIR-9** Ruihua Song, Min Zhang, Tetsuya Sakai, Makoto P. Kato, Yiqun Liu, Miho Sugimoto, Qinglei Wang, Naoki Orii: Overview of the NTCIR-9 INTENT Task. NTCIR 2011, 2011."
    resources:
      - "[interleaving](https://github.com/mpkato/interleaving): a Python library for interleaving-based online evaluation"
      - "[openliveq](https://github.com/mpkato/openliveq) and [mobileclick-eval](https://github.com/mpkato/mobileclick-eval): evaluation tools for NTCIR tasks"
  - id: "analogy-based-ir"
    title: "Analogy-based Information Retrieval"
    period: "2008 – 2012"
    funding: "JSPS Research Fellowship DC1 (FY2010–FY2012) / Kyoto Univ. GCOE (FY2009) / IPA MITOH Youth Program (2008)"
    image: "/images/MapAnalogySearch.png"
    summary: >
      We studied search by examples and analogies, which retrieves information
      in unfamiliar domains using what users already know: Query by Analogical
      Example, a relational search method using Web search engine indices; a
      restaurant search that lets users search unfamiliar places as if they
      were in their hometown; RhythMiXearch, which finds unknown music by
      mixing known music; and a Web image search method for abstract query
      terms based on social tags.
    publications:
      - "**SIGIR 2012** Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka: Content-based Retrieval for Heterogeneous Domains: Domain Adaptation by Relative Aggregation Points. In Proc. of the 35th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2012), pp. 811-820, 2012."
      - "**CIKM 2009** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Query by Analogical Example: Relational Search Using Web Search Engine Indices. In Proc. of the 18th ACM International Conference on Information and Knowledge Management (CIKM 2009), pp. 27-36, 2009."
      - "**ISMIR 2009** Makoto P. Kato: RhythMiXearch: Searching for Unknown Music by Mixing Known Music. In Proc. of 10th International Society for Music Information Retrieval Conference (ISMIR 2009), pp. 477-482, 2009."
      - "**WISE 2008** Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka: Can Social Tagging Improve Web Image Search? In Proc. of the 9th International Conference on Web Information Systems Engineering (WISE 2008), pp. 235-249, 2008. *(Kambayashi Best Paper Award)*"
    resources:
      - "[QAE and GORD datasets](/data/) created in these studies"
---
