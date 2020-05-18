
# Datasets-for-Sentiment-Analysis
Benchmark datasets for sentiment analysis: For these days, I try to find some datasets for sentiment analysis, which cost me a lot of time. Thus, I hope to collect the benchmark datasets (e.g., SST, SST-1, SST-2, Yelp, IMDB) here. If you have any more information, please feel free to contact me.

 ## Sentiment Analysis
### **SST-1/SST-2**
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
 ### **IMDB**
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
### **Yelp**
  The Yelp reviews polarity dataset is constructed by considering stars 1 and 2 negative, and 3 and 4 positive. For each polarity 280,000 training samples and 19,000 testing samples are take randomly. In total there are 560,000 trainig samples and 38,000 testing samples. Negative polarity is class 1, and positive class 2.
  The files train.csv and test.csv contain all the training samples as comma-sparated values. There are 2 columns in them, corresponding to class index (1 and 2) and review text. The review texts are escaped using double quotes ("), and any internal double quote is escaped by 2 double quotes (""). New lines are escaped by a backslash followed with an "n" character,
that is "\n".
 
 

     @article{zhangCharacterlevelConvolutionalNetworks2015,
        archivePrefix = {arXiv},
        eprinttype = {arxiv},
        eprint = {1509.01626},
        primaryClass = {cs},
        title = {Character-Level {{Convolutional Networks}} for {{Text Classification}}}
        journal = {arXiv:1509.01626 [cs]},
        author = {Zhang, Xiang and Zhao, Junbo and LeCun, Yann},
        month = sep,
        year = {2015},
      }

  data_url = "https://s3.amazonaws.com/fast-ai-nlp/yelp_review_polarity_csv.tgz"
 ###  **Sentiment140**
  Sentiment140 consists of Twitter messages with emoticons, which are used as noisy labels for sentiment classification. For more detailed information please refer to the paper.
  url = "http://help.sentiment140.com/home"
  data_url = "http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip"
 ## Multi-domain Sentiment Analysis

 ## Aspect-based Sentiment Analysis

 ## Multi-lingual Sentiment Analysis
 ## Aspect-based Sentiment Analysis
 ### SemEval 14 Task 4
 
    @inproceedings{pontiki-etal-2014-semeval,
       title = "{S}em{E}val-2014 Task 4: Aspect Based Sentiment Analysis",
       author = "Pontiki, Maria  and
         Galanis, Dimitris  and
         Pavlopoulos, John  and
         Papageorgiou, Harris  and
         Androutsopoulos, Ion  and
         Manandhar, Suresh",
       booktitle = "Proceedings of the 8th International Workshop on Semantic Evaluation ({S}em{E}val 2014)",
       month = aug,
       year = "2014",
       address = "Dublin, Ireland",
       publisher = "Association for Computational Linguistics",
       url = "https://www.aclweb.org/anthology/S14-2004",
       doi = "10.3115/v1/S14-2004",
       pages = "27--35",
    }
   
   data-url = "http://alt.qcri.org/semeval2014/task4/"
   - Restaurants
   - Laptops
 ### SemEval 15 Task 12
     @inproceedings{pontiki2015semeval,
    title={Semeval-2015 task 12: Aspect based sentiment analysis},
    author={Pontiki, Maria and Galanis, Dimitrios and Papageorgiou, Harris and Manandhar, Suresh and Androutsopoulos, Ion},
    booktitle={Proceedings of the 9th international workshop on semantic evaluation (SemEval 2015)},
    pages={486--495},
    year={2015}
    }
   data-url = "http://alt.qcri.org/semeval2015/task12/"
 ### SemEval 16 Task 5
    @inproceedings{pontiki2016semeval,
    title={Semeval-2016 task 5: Aspect based sentiment analysis},
    author={Pontiki, Maria and Galanis, Dimitrios and Papageorgiou, Haris and Androutsopoulos, Ion and Manandhar, Suresh and Al-Smadi, Mohammad and Al-Ayyoub, Mahmoud and Zhao, Yanyan and Qin, Bing and De Clercq, Orph{\'e}e and others},
    booktitle={10th International Workshop on Semantic Evaluation (SemEval 2016)},
    year={2016}
    }
   data-url = "http://alt.qcri.org/semeval2016/task5/"
 ### Twitter
 As people tend to post comments for the celebrities, products, and companies, we use these keywords (such as "bill gates", "taylor swift", "xbox", "windows 7", "google") to query the Twitter API. After obtaining the tweets, we manually annotate the sentiment labels (negative, neutral, positive) for these targets. In order to eliminate the effects of data imbalance problem, we randomly sample the tweets and make the data balanced. The negative, neutral, positive classes account for 25%, 50%, 25%, respectively. Training data consists of 6,248 tweets, and testing data has 692 tweets.
 
    @inproceedings{dong2014adaptive,
     title={Adaptive recursive neural network for target-dependent twitter sentiment classification},
     author={Dong, Li and Wei, Furu and Tan, Chuanqi and Tang, Duyu and Zhou, Ming and Xu, Ke},
     booktitle={Proceedings of the 52nd annual meeting of the association for computational linguistics (volume 2: Short papers)},
     pages={49--54},
     year={2014}
    }
    
   data-url = ""
 ### Sentihood
    @article{saeidi2016sentihood,
     title={Sentihood: Targeted aspect based sentiment analysis dataset for urban neighbourhoods},
     author={Saeidi, Marzieh and Bouchard, Guillaume and Liakata, Maria and Riedel, Sebastian},
     journal={arXiv preprint arXiv:1610.03771},
     year={2016}
    }
   data-url = "http://annotate-neighborhood.com/download/sentihood-train.json, http://annotate-neighborhood.com/download/sentihood-dev.json, http://annotate-neighborhood.com/download/sentihood-test.json"

 ### MPQA 
    @inproceedings{deng2015mpqa,
     title={Mpqa 3.0: An entity/event-level sentiment corpus},
     author={Deng, Lingjia and Wiebe, Janyce},
     booktitle={Proceedings of the 2015 conference of the North American chapter of the association for computational linguistics: human language technologies},
     pages={1323--1328},
     year={2015}
    }
   data-url = "https://mpqa.cs.pitt.edu/corpora/mpqa_corpus/"
 ### tripAdvisor
 Three equally experienced annotators provided sentence-level annotations of a subset of 500 randomly selected reviews from the publicly available TripAdvisor dataset. The full TripAdvisor dataset consists of 235,793 hotel reviews crawled over a period of one month. In addition to the review text, each review comes with a hotel identifier, an overall rating and optional aspect-specific ratings for the following seven aspects: Rooms, Cleanliness, Value, Service, Location, Checkin, and Business. All review-level ratings are on a discrete ordinal scale from 1 to 5 (with -1 indicating that an aspect-specific rating was not provided by the reviewer).
 
    @inproceedings{wang2010latent,
     title={Latent aspect rating analysis on review text data: a rating regression approach},
     author={Wang, Hongning and Lu, Yue and Zhai, Chengxiang},
     booktitle={Proceedings of the 16th ACM SIGKDD international conference on Knowledge discovery and data mining},
     pages={783--792},
     year={2010}
    }
 
 ### Michell
    @inproceedings{mitchell2013open,
     title={Open domain targeted sentiment},
     author={Mitchell, Margaret and Aguilar, Jacqui and Wilson, Theresa and Van Durme, Benjamin},
     booktitle={Proceedings of the 2013 Conference on Empirical Methods in Natural Language Processing},
     pages={1643--1654},
     year={2013}
    }
   data-url = ""
 > **Note**: Some of the datasets can be downloaded from my google drive [https://drive.google.com/open?id=10FANFJX2de39tBs1ntUiRTd_ssQjXhsT]. More detail will be added soon.


