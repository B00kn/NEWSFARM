# NEWSFARM
A Large-scale Chinese Corpus of Long News Summarization
## Introduction
The current work on summarization datasets has made some progress, but suffers from the following problems. 
(1) Insufficient number of text summarization datasets. 
(2) The development of various datasets is unbalanced. While the English datasets are well developed, the other language datasets lag behind. 
(3) The amount of data in the dataset is insufficient. 
(4) Dirty data during the construction of summarization datasets are not classified in detail, and the data cleaning algorithm is too simple to handle dirty data well.

NEWSFARM is a large-scale Chinese long news summarization corpus, containing more than 220K Chinese long news and summaries written by professional editors or authors.
The dataset is introduced in (NEWSFARM: A Large-scale Chinese Corpus of Long News Summarization)

## Properties
The comparison result of NEWSFARM to other datasets is shown in the table below. For Chinese dataset, length is the number of Chinese characters, while for English, it is the number of words.

| Dataset | NEWSFARM | CLES | LCSTS | CNN/DM |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| #docs(total/train/val/test) | 224,480/185,125/18,123/21,232 | 103,893/95,000/3,839/5,000 | 2,412,163/2,400,391/10,666/1,106 | 312,085/287,227/13,368/11,490 |
| compression ratio(words/sentences) | 0.92/0.92 | 0.93/0.92 | 0.83/0.90 | 0.93/0.88 |
| avg.document length | 1,048.00/39.29 | 1,584.00/36.00 | 108.80/10.13 | 687.09/31.66 |
| avg.summary length | 86.90/3.05 | 106.00/3.00 | 19.00/1.00 | 48.49/3.73 |
