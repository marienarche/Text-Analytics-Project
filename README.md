# Text-Analytics-Project

# Sentiment Analysis for Financial News

### Text Analytics A.Y. 2022/23


## DATASET
The dataset that will be analysed is a collection of 4840 sentences. The provided collection has been annotated by 16 people, all with relevant background knowledge in finances. So, in the end we have the dataset with two columns, in the first we have the provided annotation, a sentiment (in our case the target class) which can be either “positive, negative, or neutral”, and in the second, we have the sentence itself. Three of the annotators were researchers and the remaining 13 annotators were master’s students at Aalto University School of Business with majors primarily in finance, accounting, and economics.
As there are a lot of overlapping annotations, there is also defined a majority vote for each instance sentence and therefore, four alternative reference datasets are provided together with the original one. The following collections of data is separated by the strength of majority vote: 
* sentences with 100% agreement [file=Sentences_AllAgree.txt].
* sentences with more than 75% agreement [file=Sentences_75Agree.txt].
* sentences with more than 66% agreement [file=Sentences_66Agree.txt].
* sentences with more than 50% agreement [file=Sentences_50Agree.txt].

All reference datasets files are in a machine-readable "@"-separated format.

## GENERAL IDEA
The objective of the work is to classify each example sentence into a positive, negative, or neutral category by considering only the information explicitly available in the given sentence. 

The idea is to at first, understand the semantics of data, and pre-process for further analysis, which should comprise with both unsupervised techniques of clustering and most importantly both supervised and unsupervised techniques of classification. For this step we will split the dataset into Train, Validation and Test sets in such a way to be able to properly train the specific amount of data, validate the different techniques and identify the best one, and finally tests the best model on unknown data. As for evaluation, we will use measures such as accuracy, recall, precision, F1-score, as well as ROC-curve and confusion matrix for better representation. 

## TOPIC
Train the best classification model in such a way that in the face of a new set of data relating to the financial theme, it can label the sentiment related to individual news and then exploit it as a possible indicator to act in the market.

## TASKS
*	Data Understanding and Preparation
*	Classification Supervised
*	Classification Unsupervised
*	Clustering
