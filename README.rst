========
VAE-NTMs
========
**VAE-NTMs** is a class of neural topic models (NTMs) that uses amortized variational inference technique to compute the approximate posterior distribution.

Models
------
In this paper, we have analyzed the effect of dropout in VAE-based neural topic models. We have chosen three widely used neural topic models,
which are as follows:

* **CTM**: Bianchi, F., Terragni, S., and Hovy, D. (2021). `Pre-training is a Hot Topic: Contextualized Document Embeddings Improve Topic Coherence`. ACL. https://aclanthology.org/2021.acl-short.96/
* **ProdLDA**: Akash Srivastava and Charles Sutton. (2017). `Autoencoding variational inference for topic models`. ICLR. https://openreview.net/forum?id=BybtVK9lg
* **ETM**: Adji B. Dieng, Francisco J. R. Ruiz, and David M. Blei. (2020). Topic modeling in embedding spaces. TACL. https://doi.org/10.1162/tacl_a_00325

Datasets
--------
We have used the following datasets:

* **20NG**: https://github.com/MIND-Lab/OCTIS/tree/master/preprocessed_datasets/20NewsGroup
* **BBC**: https://github.com/MIND-Lab/OCTIS/tree/master/preprocessed_datasets/BBC_News
* **Wiki40B**: https://www.tensorflow.org/datasets/catalog/wiki40b
* **AllNews**: https://www.kaggle.com/datasets/snapcrack/all-the-news

Tutorials
---------
.. |colab1| image:: https://colab.research.google.com/assets/colab-badge.svg
    :target: https://colab.research.google.com/github/AdhyaSuman/NTMs_Dropout_Analysis/blob/master/examples/QuantitativeEvaluation.ipynb
    :alt: Open In Colab

+----------------------------------------------------------------------+----------+
| Name                                                                 | Link     |
+======================================================================+==========+
| Quantitative evaluation of topic quality and document classification | |colab1| |
+----------------------------------------------------------------------+----------+

Acknowledgment
--------------
All experiments are conducted using OCTIS_ which is an integrated framework for topic modeling.

**OCTIS**: Silvia Terragni, Elisabetta Fersini, Bruno Giovanni Galuzzi, Pietro Tropeano, and Antonio Candelieri. (2021). `OCTIS: Comparing and Optimizing Topic models is Simple!`. EACL. https://www.aclweb.org/anthology/2021.eacl-demos.31/

.. _OCTIS: https://github.com/MIND-Lab/OCTIS

Citation
--------
Will be available soon..!!
