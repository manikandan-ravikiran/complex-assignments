# Complex Assignments

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/manikandan-ravikiran/cs6460-proj/master)

## Introduction
This repository includes codes related to https://tinyurl.com/yay77mdy, https://arxiv.org/abs/2004.01549 and https://arxiv.org/abs/2003.07019 focusing on Keyphrase Extraction, Keyphrase Classification & Keyphrase-Rubric Relationship Extraction from Complex Assignments. We analysize and study multiple supervised and unsupervised approaches for all the three tasks.


## Dependencies
* Python3 (Tested on python 3.7)
* Jupyter Notebook
* Scikit-learn
* Transformers(Hugging Face)
* pke 
* eli5


## Installation

First, clone the repository:
```
https://github.com/manikandan-ravikiran/cs6460-proj.git
```

Install requirements.
```
pip install -r requirements.txt
pip install git+https://github.com/boudinfl/pke.git
python -m nltk.downloader stopwords
python -m nltk.downloader universal_tagset
python -m spacy download en # download the english model
pip install spacy
pip install en-core-web-sm
```


*NOTE:*  The, datasets are already processsed, features are extracted and pickled for replication purposes. Due to privacy restrictions we dont release any datasets in raw format. If you need data for research purposes. Please send an email to mravikiran3@gatech.edu along with details on your research. 

The codes are in form of Ipython notebook, you can deploy directly in binder and execute. Please click on the binder build icon. (*Please note the due to requirement of GPU and privacy of datasets binder can run only few of the experiments. For full fledged run, use a GPU machine*) 

## Code Organization
* The code organization is with respect to research questions in paper https://tinyurl.com/yay77mdy.
* Each *RQx (RQ1.1,RQ1.2,...RQ3.2)* fold answers one or more of the research question and contains two sub folders namely **code** and **data**. Each of the RQx folder code could be run individually without any cross dependency across the project, so in a sense the codes are self contained.


## Result Reproducibility & Execution

Following details shows relationship to code and Tables of results in https://manikandan-ravikiran.github.io/files/edtech1.pdf. Each code could be run individually without any cross dependency. To reproduce a results, execute corresponding Ipython notebook as mentioned below. Further each of the jupyter notebook includes comments and neccessary information for execution.

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

# Cite


If you find this repo useful in your research, please consider citing the following papers:
```
@article{Ravikiran2020UnsupervisedKR,
title={Unsupervised Keyphrase Rubric Relationship Classification in Complex Assignments},
author={Manikandan Ravikiran},
journal={ArXiv},
year={2020},
volume={abs/2004.01549}
}

@article{Ravikiran2020KeyPC,
title={Key Phrase Classification in Complex Assignments},
author={Manikandan Ravikiran},
journal={ArXiv},
year={2020},
volume={abs/2003.07019}
}
```
