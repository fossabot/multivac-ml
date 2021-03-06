### Word2Vec

#### Download
https://www.kaggle.com/mozzie/apache-spark-word2vec-model/downloads/apache-spark-word2vec-model.zip/1

Apache Spark 2.3 is used to extract more than 6 million phrases from 200,000 English Wikipedia pages. Here is the process of cleaning, extracting keywords, and training Word2Vec model:

* Merging page's Title and its Text
* Sentence detection (spark-nlp)
* Tokenizer (spark-nlp)
* Normalizer (spark-nlp) POS Tagger (spark-nlp) Chuning with grammar rules to detect both uni-grams and multi-grams (spark-nlp)
* Stop words remover (Spark ML)
* Training and transforming Word2Vec Model (Spark ML)

## Code of Conduct

This, and all github.com/multivacplatform projects, are under the [Multivac Platform Open Source Code of Conduct](https://github.com/multivacplatform/code-of-conduct/blob/master/code-of-conduct.md). Additionally, see the [Typelevel Code of Conduct](http://typelevel.org/conduct) for specific examples of harassing behavior that are not tolerated.

## Copyright and License

Code and documentation copyright (c) 2018 [ISCPIF - CNRS](http://iscpif.fr). Code released under the [MIT license](https://github.com/multivacplatform/multivac-ml/blob/master/LICENSE).
