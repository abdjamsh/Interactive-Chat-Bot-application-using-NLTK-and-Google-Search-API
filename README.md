# Interactive-Chat-Bot-application-using-NLTK-and-Google-Search-API

Libraries used:
import io

import random

import string

import warnings
import numpy as np
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity
import warnings
warnings.filterwarnings('ignore')

import nltk
from nltk.stem import WordNetLemmatizer
import openpyxl

Pre-processing tasks: 
1.	Case Folding (Lower Case)
2.	Sentence Tokenization
3.	Word Tokenization
4.	Lemmatization
5.	Stop word Removal


Dataset Description:
	Name:  extracted from wikipedia
            URL: https://en.wikipedia.org/
	No of words:9 documents(2626+1037+1748+351+1403+1324+354+1049+379)
No of unique words: (1028+457+675+171+531+528+189+344+200)

Block Diagram: 
 


Description 
This project is aimed to implement a web-based chat bot to assist students to learn the computer science related subjects using tools that expose artificial intelligence methods such as natural language understanding. Allowing users to interact with the chat bot using natural language input and to train the chat bot using appropriate methods so it will be able to generate a response. The prototype was mainly implemented using NLTK library.


Output:
         Description of output:
User will start with a greeting and proceed with their query regarding computer science related domain. Bot will take this query and search in the dataset and corresponding output is displayed. If the query doesn’t match in the data set it will give appropriate message to handle the query.
