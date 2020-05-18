# Datasets-for-Sentiment-Analysis
Benchmark datasets for sentiment analysis: For these days, I try to find some datasets for sentiment analysis, which cost me a lot of time. Thus, I hope to collect the benchmark datasets (e.g., SST, SST-1, SST-2, Yelp, IMDB) here. If you have any more information, please feel free to contact me.

1. Sentiment Analysis
  - SST-1/SST-2
  The Stanford Sentiment Treebank consists of sentences from movie reviews and human annotations of their sentiment. The task is to predict the sentiment of a given sentence. We use the two-way (positive/negative) class split, and use onlyvsentence-level labels.
  data_url="https://firebasestorage.googleapis.com/v0/b/mtl-sentence-representations.appspot.com/o/data%2FSST-2.zip?alt=media&token=aabc5f6b-e466-44a2-b9b4-cf6337f84ac8",
  @inproceedings{socher2013recursive,
    title={Recursive deep models for semantic compositionality over a sentiment treebank},
    author={Socher, Richard and Perelygin, Alex and Wu, Jean and Chuang, Jason and Manning, Christopher D and Ng, Andrew and Potts, Christopher},
    booktitle={Proceedings of the 2013 conference on empirical methods in natural language processing},
    pages={1631--1642},
    year={2013}
  }
  url="https://nlp.stanford.edu/sentiment/index.html",
  - IMDB
  Large Movie Review Dataset.
  This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. We provide a set of 25,000 highly polar movie reviews for training, and 25,000 for testing. There is additional unlabeled data for use as well.
  @InProceedings{maas-EtAl:2011:ACL-HLT2011,
    author    = {Maas, Andrew L.  and  Daly, Raymond E.  and  Pham, Peter T.  and  Huang, Dan  and  Ng, Andrew Y.  and  Potts, Christopher},
    title     = {Learning Word Vectors for Sentiment Analysis},
    booktitle = {Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies},
    month     = {June},
    year      = {2011},
    address   = {Portland, Oregon, USA},
    publisher = {Association for Computational Linguistics},
    pages     = {142--150}
  }
  data_url = "http://ai.stanford.edu/~amaas/data/sentiment/aclImdb_v1.tar.gz"
  - Yelp
  The Yelp reviews polarity dataset is constructed by considering stars 1 and 2 negative, and 3 and 4 positive. For each polarity 280,000 training samples and 19,000 testing samples are take randomly. In total there are 560,000 trainig samples and 38,000 testing samples. Negative polarity is class 1, and positive class 2.
  The files train.csv and test.csv contain all the training samples as comma-sparated values. There are 2 columns in them, corresponding to class index (1 and 2) and review text. The review texts are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). New lines are escaped by a backslash followed with an "n" character,
that is "\n".
  '''
  @article{zhangCharacterlevelConvolutionalNetworks2015,
    archivePrefix = {arXiv},
    eprinttype = {arxiv},
    eprint = {1509.01626},
    primaryClass = {cs},
    title = {Character-Level {{Convolutional Networks}} for {{Text Classification}}},
    abstract = {This article offers an empirical exploration on the use of character-level convolutional networks (ConvNets) for text classification. We constructed several large-scale datasets to show that character-level convolutional networks could achieve state-of-the-art or competitive results. Comparisons are offered against traditional models such as bag of words, n-grams and their TFIDF variants, and deep learning models such as word-based ConvNets and recurrent neural networks.},
    journal = {arXiv:1509.01626 [cs]},
    author = {Zhang, Xiang and Zhao, Junbo and LeCun, Yann},
    month = sep,
    year = {2015},
  }
  '''
  data_url = "https://s3.amazonaws.com/fast-ai-nlp/yelp_review_polarity_csv.tgz"
  - Sentiment140
  Sentiment140 consists of Twitter messages with emoticons, which are used as noisy labels for sentiment classification. For more detailed information please refer to the paper.
  url = "http://help.sentiment140.com/home"
  data_url = "http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip"
2. Multi-domain Sentiment Analysis

3. Aspect-based Sentiment Analysis

4. Multi-lingual Sentiment Analysis

5. Aspect-based Sentiment Analysis
  - SemEval 14
    - Restaurants
    - Laptops
  - SemEval 15
  - SemEval 16
  - Twitter
  
  More detail will be added soon.


