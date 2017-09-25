Python Packages:
1. Python 2.7
2. pip install Anaconda
3. pip install pydotplus
4. pip install seaborn
5. pip install wordcloud

Keep the file in same folder as the notebook file.


Required Imports:

import pandas as pd
import csv
import matplotlib.pyplot as plt
from IPython.display import display
%matplotlib inline
from sklearn.cross_validation import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.metrics import confusion_matrix
from sklearn.metrics import classification_report
import numpy as np
import datetime
import calendar
import seaborn as sns
from sklearn import preprocessing
from sklearn.ensemble import RandomForestClassifier
from sklearn.tree import DecisionTreeClassifier,export_graphviz
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.cluster import KMeans
from sklearn.metrics import adjusted_rand_score
from sklearn.metrics.pairwise import cosine_similarity
from wordcloud import WordCloud, STOPWORDS

