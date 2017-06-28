# SemEval-2013: Sentiment Analysis in Twitter
Sentence-Level Sentiment Analysis

## Descriptions
**One model to learn them all** (both language model and sentiment analysis)
![alt text](https://raw.githubusercontent.com/peace195/Semeval2013/master/model.png)

## Version
* se-v1: using sum all lstm output unit to predict sentiment label.
* se-v2: using [sentiment embedding](http://aclweb.org/anthology/P14-1146) instead of one-hot vector.
* se-v3: using sum all lstm output unit of **[sentiment word](https://github.com/peace195/sentiment-analysis-in-twitter/tree/master/dict)** to predict sentiment label.

## Data & Result
* [https://www.cs.york.ac.uk/semeval-2013/task2.html](https://www.cs.york.ac.uk/semeval-2013/task2.html)
* 67% accuracy rate

## Author
**Binh Thanh Do**