========
VAE-NTMs
========
**VAE-NTMs** is a class of neural topic models (NTMs) that uses amortized variational inference technique to compute the approximate posterior distribution.

Models
------
In this paper, we have analyzed the effect of dropout in VAE-based neural topic models. We have chosen three widely used neural topic models,
which are as follows:

.. raw:: html

 <img src="https://github.com/AdhyaSuman/NTMs_Dropout_Analysis/blob/master/misc/Dropout.png" align="right" width="300px" alt="right-aligned logo in README">

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

How to cite this work?
---------------------
This work has been accepted at EACL 2023!

Read the paper:

1. `ACL Anthology`_

2. `ArXiv`_

If you decide to use this resource, please cite:

.. _`ACL Anthology`: https://aclanthology.org/2023.eacl-main.162/

.. _`arXiv`: https://arxiv.org/abs/2303.15350


::

    @inproceedings{adhya-etal-2023-neural,
    title = "Do Neural Topic Models Really Need Dropout? Analysis of the Effect of Dropout in Topic Modeling",
    author = "Adhya, Suman  and
      Lahiri, Avishek  and
      Sanyal, Debarshi Kumar",
    booktitle = "Proceedings of the 17th Conference of the European Chapter of the Association for Computational Linguistics",
    month = may,
    year = "2023",
    address = "Dubrovnik, Croatia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.eacl-main.162",
    pages = "2220--2229",
    abstract = "Dropout is a widely used regularization trick to resolve the overfitting issue in large feedforward neural networks trained on a small dataset, which performs poorly on the held-out test subset. Although the effectiveness of this regularization trick has been extensively studied for convolutional neural networks, there is a lack of analysis of it for unsupervised models and in particular, VAE-based neural topic models. In this paper, we have analyzed the consequences of dropout in the encoder as well as in the decoder of the VAE architecture in three widely used neural topic models, namely, contextualized topic model (CTM), ProdLDA, and embedded topic model (ETM) using four publicly available datasets. We characterize the dropout effect on these models in terms of the quality and predictive performance of the generated topics."
    }
  
