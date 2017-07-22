# NATURAL-LANGUAGE-PROCESSING
-------------------------------

## Auto-summarization
------------------------
Natural Language Processing

* Tasks in NLP:
1. Tokenization
2. Stopword Removal
3. N-Gram (common word identification)
4. Word sense disambiguity
5. Parts-of-speech
6. Stemming (removing ends of words)

* Typical Machine Learning Workflow:
1. Pick a problem
2. Represent Data
3. Apply an algorithm

* Auto-summarizing Text
------------------------------
1. Rule Based approach
a. Find the most important words
b. Compute significance score for each word
c. Pick the top most significant sentences

2. Machine Learning based approach
a. Feature extraction using bag of words model
b. k-means clustering - to identify topic/themes
c. K-nearest neighbors model for classifying text into topics/themes

------------------------------------------------------------------------------------------------------------------------------------------
# Natural Language Processing
-------------------------------
## Sentiment Analysis
----------------------

*  Changing online behavior patterns
 - (Surf/Browse) - (Search-Find-Obtain) - (Share-Discover)

* Sentiment Analysis Systems
i. Collect Opinions
ii. Extract Information
iii. Act

* Information Embedded in Opinions
-------------------------------------------
i. Polarity - Positive / Negative;
ii. Subjectivity - Subjective / Objective;
iii. Aspects - Part / Whole;

* Simple Rule Based Classifier
---------------------------------
1. Split text fragments into words;
2. Calculate polarity of words;
3. Aggregate word polarities;

* Implementing rule-based approach using VADER
---------------------------------------------------------
1. Extract corpus;
2. Classify with VADER - Positive or Negative - Compound Score;
3. Measure the accuracy;

* ML-based Approach
-------------------------
* Naive Bayes
--------------
1. Split Corpus - test and training dataset;
2. Define Vocabulary; (training Only);
3. Extract features - tuples;
4. Train classifier;
5. Classify test data;
6. Measure Accuracy;
