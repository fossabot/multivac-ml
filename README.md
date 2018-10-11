# multivac-ml [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/multivacplatform/multivac-ml/blob/master/LICENSE) [![Build Status](https://travis-ci.org/multivacplatform/multivac-ml.svg?branch=master)](https://travis-ci.org/multivacplatform/multivac-ml) [![multivac discuss](https://img.shields.io/badge/multivac-discuss-ff69b4.svg)](https://discourse.iscpif.fr/c/multivac) [![multivac channel](https://img.shields.io/badge/multivac-chat-ff69b4.svg)](https://chat.iscpif.fr/channel/multivac)

Already trained Apache Spark's ML Pipeline for NLP, Classification, etc.


### Trained ML Models

Plesae download already trained ML models form here:

#### Word2Vec
https://www.kaggle.com/mozzie/apache-spark-word2vec-model/downloads/apache-spark-word2vec-model.zip/1

Apache Spark 2.3 is used to extract more than 6 million phrases from 200,000 English Wikipedia pages. Here is the process of cleaning, extracting keywords, and training Word2Vec model:

* Merging page's Title and its Text
* Sentence detection (spark-nlp)
* Tokenizer (spark-nlp)
* Normalizer (spark-nlp) POS Tagger (spark-nlp) Chuning with grammar rules to detect both uni-grams and multi-grams (spark-nlp)
* Stop words remover (Spark ML)
* Training and transforming Word2Vec Model (Spark ML)


##### TF-IDF
coming soon!


## Code of Conduct

This, and all github.com/multivacplatform projects, are under the [Multivac Platform Open Source Code of Conduct](https://github.com/multivacplatform/code-of-conduct/blob/master/code-of-conduct.md). Additionally, see the [Typelevel Code of Conduct](http://typelevel.org/conduct) for specific examples of harassing behavior that are not tolerated.

## Copyright and License

Code and documentation copyright (c) 2018 [ISCPIF - CNRS](http://iscpif.fr). Code released under the [MIT license](https://github.com/multivacplatform/multivac-ml/blob/master/LICENSE).
