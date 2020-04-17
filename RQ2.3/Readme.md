# Supervised Keyphrase Classification - Interpretability

This folder consists of codes for extraction of lime interpretability models for both SVM+TFIDF and language models (BERT and RoBERTA)

## Folder Organization

* **Code** - Consists of ipynb notebooks to produce LIME interpretability for each of the models mentioned in the introduction.
* **Data** - Consists of tsv files used for input, along with some additional pickle files needed for purpose of BERT model.
* **Results** - Results consists interpretability html files which we got for the fold-2 of dataset using both SVM+BERT and SVM+TFIDF.


*NOTE:* The overall process for extraction of lime interpretability take 8hrs of 1 Tesla k-80 GPU. As such the code requires high computation infrastrcture.
