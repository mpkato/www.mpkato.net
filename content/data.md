---
title: "Data and Tools"
date: 2019-03-10T12:57:45+09:00
---

## Tools

- [interleaving](https://github.com/mpkato/interleaving): A python library for conducting interleaving, which compares two or multiple rankers based on observed user clicks by interleaving their results.
- [openliveq](https://github.com/mpkato/openliveq): A python package for NTCIR OpenLiveQ
- [mobileclick-eval](https://github.com/mpkato/mobileclick-eval): Evaluation scripts for NTCIR-12 MobileClick-2

## Datasets
### Experimental data for Optimizing Search Result Presentation
Available are search behavior data of 256 users that were recorded in desktop and mobile search tasks, intent votes of 20 users for NTCIR INTENT-1 and INTENT-2 topics,
and features extracted for learning to rank in the NTCIR INTENT-1 and INTENT-2 test collections.

#### Download
- [Search behavior data](https://www.dropbox.com/s/bs6abx0kfntdcwl/search_behavior_data.tar.gz)
- [Intent votes](https://www.dropbox.com/s/jfobsd6oqsdblyw/intent_votes.tar.gz)
- [Learning-to-rank features](https://www.dropbox.com/s/om2dthrihfsrr3r/learning_to_rank.tar.gz)

#### Related Publications
- Makoto P. Kato, Katsumi Tanaka (2016) To Suggest, or Not to Suggest for Queries with Diverse Intents: Optimizing Search Result Presentation, In Proc. of the 9th ACM International Conference on Web Search and Data Mining (WSDM2016)

### Test Collections for Conversational Relevance Feedback
Two test collections are available for evaluating conversational relevance feedback (CRF) systems. Details are coming soon…

#### Download
- [Celebrity Test Collection](https://www.dropbox.com/s/l7ndf3ut8mr9l7l/celebrity.tar.gz)
- [Restaurant Test Collection](https://www.dropbox.com/s/glh4ehgjagjtcp6/restaurant.tar.gz)

#### Related Publications
- wait for our upcoming paper…

### Cognitive Relevance Dataset
This dataset contains relevance judgments in terms of cognitive relevance, by which you may evaluate your comprehensibility, coverage, subjectivity/objectivity, concreteness/abstractness-aware search systems. For example, topics include “easy-to-understand black hole” and “subjective Macbook Pro”

#### Download
- [Cognitive Relevance Dataset](https://www.dropbox.com/s/vebpo8j6lyqr101/CognitiveRelevanceDataset.zip)

#### Related Publications
- Makoto P. Kato, Takehiro Yamamoto, Hiroaki Ohshima, Katsumi Tanaka (2014) Investigating Users’ Query Formulations for Cognitive Search Intents, In Proc. of the 37th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2014)

### Geographic Object Retrieval Dataset (GORD)
This dataset contains search intents, restaurant objects, and relevance judgments created to evaluate content-based retrieval in heterogeneous domains. This can be used not only for content-based retrieval, but also for situation-based restaurant retrieval.

#### Download
- [GORD Ver. 1.0](https://www.dropbox.com/s/0fxjtfimmc81mft/GORD.v1.0.zip)

#### Related Publications
- Makoto P. Kato, Hiroaki Ohshima, Katsumi Tanaka (2012) Content-based Retrieval for Heterogeneous Domains: Domain Adaptation by Relative Aggregation Points, In Proc. of the 35th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2012)


### Query by Analogical Example (QAE) Dataset
This dataset contains a set of x and y pairs between which a specific kind of relations exists. For example, there is a relation “MP3 (player)” between x=Apple and y=iPod. You can evaluate relational search systems by inputting x1, y1, and x2, and examining whether a system returns y2, where the relation between x1 and y1 is the same as that between x2 and y2.

#### Download
- [QAE-dataset](https://www.dropbox.com/s/jl68d0pd85l04eh/QAE-dataset.zip)

#### Related Publications
- Makoto P. Kato, Hiroaki Ohshima, Satoshi Oyama, Katsumi Tanaka (2009) Query by analogical example: relational search using web search engine indices, In Proc. of the 18th ACM conference on Information and knowledge management (CIKM2009)
