# Supervised Generic Keyphrase-Rubric Relationship Classification

This folder consists of codes for Generic Keyphrase-Rubric Relationship Classification involving language models [1]-[4]

## Folder Organization

* **Code** - Consists of a single ipython notebook that can run all the language model algorithms. Please note that extraction language model features requires GPU. So for extraction of feature please see [here](https://huggingface.co/transformers/model_doc/auto.html#automodelforsequenceclassification)
* **Data** - The data consists of 7 folders with features already extracted from transformers. Please note this extraction process requires well supported GPU or atleast colaboratory. 


## Citation
```
[1] Devlin, J., Chang, M., Lee, K., and Toutanova, K. (2019). “BERT: Pre-training
of Deep Bidirectional Transformers for Language Understanding”. In: Proceedings of the 2019 Conference of the North American Chapter of the Association
for Computational Linguistics: Human Language Technologies
[2] Yang, Zhilin, Dai, Zihang, Yang, Yiming, Carbonell, Jaime G., Salakhutdinov, Ruslan, and Le, Quoc V. (2019). “XLNet: Generalized Autoregressive
Pretraining for Language Understanding”. In: NeurIPS.
[3] Liu, Y., Ott, M., Goyal, N., Du, J., Joshi, M., Chen, D., Levy, O., Lewis, M.,
Zettlemoyer, L., and Stoyanov, V. (2019). “RoBERTa: A Robustly Optimized
BERT Pretraining Approach”. In: ArXiv abs/1907.11692.
[4] Lample, Guillaume and Conneau, Alexis (2019). “Cross-lingual Language
Model Pretraining”. In: NeurIPS
```
