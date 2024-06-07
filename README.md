# ThaiCoref
The repository contains the ThaiCoref dataset, the largest dataset for coreference resolution in Thai language. It also includes a model trained on this data, described in the paper  ["ThaiCoref: Thai Coreference Resolution Dataset"](https://pages.github.com/).

## Abstract 
Coreference resolution is a crucial NLP task that identifies groups of words referring to the same entity. While well-studied for other languages, Thai coreference research has been limited due to a lack of large, annotated datasets. ThaiCoref fills this gap with over 777,000 tokens, 44,000 mentions, and 10,400 entities across various text types like essays, news articles, speeches, and Wikipedia entries. The annotation scheme is based on the OntoNotes benchmark, with adjustments for Thai-specific features.

## Model
The repository also offers a model trained using this dataset with cross-lingual transfer learning. You can access and download the model from [here](https://drive.google.com/drive/folders/1-4IqEsqlXTlj6AFY64XEsIBJ93Vks2rp?usp=sharing). This model (XLM-V-TA) achieves a best F1 score of 67.88% on the test set. If you'd like to use the model, you can refer to the pipelines provided in [the s2e repository](https://github.com/yuvalkirstain/s2e-coref).

## Cite
If you use this code in your research, please cite our paper:
