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

| Dataset | NEWSFARM | LCSTS | CNN/DM |
| :---: | :---: | :---: | :---: |
| #docs(total/train/val/test) | 224,480/185,125/18,123/21,232 | 2,412,163/2,400,391/10,666/1,106 | 312,085/287,227/13,368/11,490 |
| compression ratio(words/sentences) | 0.91/0.92 | 0.83/0.90 | 0.93/0.88 |
| avg.document length | 2,228.22/23.91 | 108.80/10.13 | 687.09/31.66 |
| avg.summary length | 198.42/2.02 | 19.00/1.00 | 48.49/3.73 |

| Dataset | NEWSFARM | CNN/DM |
| :---: | :---: | :---: |
| Model   |ROUGE-1/ROUGE-2/ROUGE-L|ROUGE-1/ROUGE-2/ROUGE-L|
|TextRank |43.00/26.93/33.42|35.23/13.90/31.48|
|BertSumExt|52.65/39.61/46.91|43.23/20.24/39.63|
|Seq2seq-att|56.40/45.17/51.94|31.33/11.81/28.83|
|Pointer-gen|59.05/48.10/54.76|36.44/15.66/33.42|
|Pointer-gen+cov|53.49/41.37/48.57|39.53/17.28/36.38|
|Transformer|61.48/50.60/56.91|39.66/17.19/36.66|
|BertSumAbs|48.44/33.14/39.53|41.72/19.39/38.76|
|BertSumExtAbs|48.59/33.01/39.87|42.13/19.60/39.18|

## Sample
We selected some data from the dataset as samples, click here to get.

## Download
We split the corpus into three parts, including training, validation and test set. The data can be downloaded from the link here. The download consists of three parts: NEWSFARM, ex*NEWSFARM and ex*CNN/DM.(ex* represents the expanded dataset）If you want to get the password, please feel free to contact with us by: zangshunan@iie.ac.cn
