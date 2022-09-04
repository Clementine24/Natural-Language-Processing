In this assignment, you will explore wiki-text data and build language models and classifiers. The corpus is downloaded and extracted from wiki dumps, [enwiki2022_0201](https://dumps.wikimedia.org/enwiki/20220201/). You have the following tasks:

**Task-0.** Download the preprocessed data, enwiki_20220201.json. In the data file, each line contains a Wikipedia page with attributes, title, label, and text. There are 10,000 records in total with ten categories.

**Task-1.** Data exploring and preprocessing.

**Task-2.** Build language models: 1) Based on the processed text, build unigram, bigram, and trigram language models using Add-one smoothing and Kneser-Ney smoothing on training data set; 2) Report the perplexity of these six trained models on testing text set and explain these numbers. 3) Use each built model to generate five sentences and explain these generated sentences.

**Task-3.** Build Naive Bayes classifiers: 1) Build Naive Bayes classifiers (with Laplace smoothing) by using 30%,50%,70%, and 90% of documents as training samples and 10% for testing dataset (fixed), respectively. 2) Report Micro-F1 score and Macro-F1 score for these classifiers; explain and analyze our results.