# Complex Assignments

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/manikandan-ravikiran/cs6460-proj/master)

## Introduction
This repository includes codes related to https://manikandan-ravikiran.github.io/files/edtech1.pdf, https://arxiv.org/abs/2004.01549 and https://arxiv.org/abs/2003.07019 focusing on Keyphrase Extraction, Keyphrase Classification & Keyphrase-Rubric Relationship Extraction from Complex Assignments. We analysize and study multiple supervised and unsupervised approaches for all the three tasks.


## Dependencies
* Python3 (Tested on python 3.7)
* Jupyter Notebook
* Scikit-learn
* Transformers(Hugging Face)
* pke 

## Results
## Installation

First, clone the repository:
```
https://github.com/manikandan-ravikiran/cs6460-proj.git
```

Install requirements.
```
pip install -r requirements.txt
```

The codes are in form of Ipython notebook, you can deploy directly in binder and execute. Please click on the binder build icon.

*NOTE:* The, datasets are already processsed, features are extracted and pickled for replication purposes. Due to privacy restrictions we dont release any datasets in raw format. If you need data for research purposes. Please send an email to mravikiran3@gatech.edu along with details on your research.

## Code Organization
* The code organization is with respect to research questions in paper https://manikandan-ravikiran.github.io/files/edtech1.pdf.
* Each *RQx (RQ1.1,RQ1.2,...RQ3.2)* fold answers one or more of the research question and contains two sub folders namely **code** and **data**. Each of the RQx folder code could be run individually without any cross dependency across the project, so in a sense the codes are self contained.


## Replication & Execution

Following details shows relationship to code and Tables of results in https://manikandan-ravikiran.github.io/files/edtech1.pdf. Each code could be run individually without any cross dependency. To reproduce a results, execute corresponding Ipython notebook as mentioned below.

| Results from Paper | Code Folder|
| ------------- | ------------- |
| Table 5 (KEA/WINGUS) | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/tree/master/RQ1.1/code) |
| Table 5 (KPMINER/YAKE)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/tree/master/RQ1.2/code)   |
| Table 5 (Ranking)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/tree/master/RQ1.3/code)  |
| Table 6 (KEA)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ1.1/code/KEA.ipynb)  |
| Table 6 (Multipartite)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ1.3/code/Ranking_Approach.ipynb)  |
| Table 8 (BOW/TF-IDF)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.1/code/Traditional%20Approaches.ipynb)  |
| Table 8 (Language Models)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.2/code/Language_Models.ipynb)  |
| Table 10 (Interpretability - BERT)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.3/code/bert_interpretability.ipynb)  |
| Table 10 (Interpretability - SVM+TFIDF)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.3/code/traditional_interpretability.ipynb)  |
| Table 11 (Interpretability - BERT)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.3/code/bert_interpretability.ipynb)  |
| Table 11 (Interpretability - SVM+TFIDF)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ2.3/code/traditional_interpretability.ipynb)  |
| Table 12 (K-Means)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ3.1/code/K-Means.ipynb)  |
| Table 13 (Agglomerative)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ3.1/code/Aggolomerative.ipynb)|
| Table 14 (Spectral)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/blob/master/RQ3.1/code/Spectral%20Clustering.ipynb)|
| Table 15 (Latent Dirichlet Allocation)  | [Execute this](https://github.com/manikandan-ravikiran/cs6460-proj/tree/master/RQ3.2/code)|







[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/manikandan-ravikiran/cs6460-proj/master)
