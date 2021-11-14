# FINAL PROJECT. PART 2.  Indexing and Evaluation


_The aim of this practice is to index and evaluate a document corpus, which is a set of tweets from the World Health Organization (@WHO) account. We will figure out the performance of the system, success or failure, based on how efficiently it is retrieving data for users._

## Starting 🚀

_This project consists of a dataset of tweets from the World Health Organization named: ‘dataset_tweets_WHO.txt’
Also includes a Jupyter notebook where the code is developed._


### Pre-requirements 📋

_Needed imports_

```
from collections import defaultdict
from array import array
from nltk.stem import PorterStemmer
from nltk.corpus import stopwords
import math
import numpy as np
import collections
from numpy import linalg as la
import time
import json
import re
import unidecode
import pandas as pd
import matplotlib.pyplot as plt
import json
import nltk
from wordcloud import WordCloud
from sklearn.metrics import average_precision_score
import codecs
import multiprocessing
from gensim.models import Word2Vec
import matplotlib.pyplot as plt
import matplotlib.cm as cm
```

### Instalation 🔧

```
!pip install wordcloud
!pip install gensim
nltk.download('stopwords')
```

### Steps🔩

First part:

 * Create the inverted index.
 * Make a proposal of 5 queries.
 * Apply a TF-IDF ranking to your results.

Second part:

  * Create a ground-truth .
  * Evaluate your algorithm by using different evaluation techniques and comment in each of them how they differ, and which information gives each of them:
    * Precision@K (P@K)
    * Average Precision@K (P@K)
    * Mean Average Precision (MAP)
    * Mean Reciprocal Rank (MRR)
    * Normalized Discounted Cumulative Gain (NDCG)
  * Word2vec representation.


## Built with 🛠️

* [Jupyter Notebook] (https://jupyter.org/) 
* [Python] (https://www.python.org/)


## Authors✒️

* **Irina Kireeva** 
* **Esther Flores** 
* **Frida Gloria**

