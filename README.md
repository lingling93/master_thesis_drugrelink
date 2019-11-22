# A Comparison of Learned and Engineered Features in Network-Based Drug Repositioning

This repository contains the master thesis of Lingling Xu. Click [here](https://github.com/lingling93/master_thesis_drugrelink/blob/master/main.pdf) for the latest version.

## Build

To build as a PDF, clone the repository and use the following command:

```bash
$ latexmk -pdf -pvc main
```
## Abstract

Drug repositioning is an time-efficient and less costly way for drug design. Computational methods especially network-based approaches are applied to integrate biological knowledge and then extract feature embeddings from the network for building a binary classification model to differentiate and predict the relationship between a drug and a disease.

This thesis introduces a workflow that leverages network representation learning methods such as node2vec and edge2vec to generate learned features for Hetionet, an integrated heterogeneous network with comparatively rich biological data (47k nodes and 2000k edges). After optimizing the parameters of node2vec and edge2vec, compare the performances of models trained by learned features and engineered features to evaluate the quality of feature embeddings. At the end, well trained models are used to predict new edges between drug nodes and disease nodes. Case study of HDAC-6 inhibitor, vorinostat, is provided. Diseases that can be potentially treated by vorinostat are predicted and some of them are validated by reserches done by other scientists. Another case study is to predict novel drug candidates for \ac{AD}, also, some of the predictions have been reported. In summary, learned features from node2vec and edge2vec can catch structure and semantic characteristics of the network. And high-quality learned feature embeddings can replace engineered features for drug repositioning tasks.
