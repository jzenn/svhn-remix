# The SVHN Dataset Is Deceptive for Probabilistic Generative Models Due to a Distribution Mismatch
<div id="top"></div>

  [![arxiv-link](https://img.shields.io/badge/Paper-PDF-red?style=flat&logo=arXiv&logoColor=red)](.)
  [![Project Page](https://img.shields.io/badge/Project%20Page-610208)](https://jzenn.github.io/svhn-remix)
  [![Download](https://img.shields.io/badge/Download-074161)](https://jzenn.github.io/svhn-remix#download)

  <span><a href="https://timx.me" target="_blank">Tim&nbsp;Z.&nbsp;Xiao</a><sup>&#42;</sup> &emsp; <b>&middot;</b> &emsp;
  <a href="https://jzenn.github.io" target="_blank">Johannes&nbsp;Zenn</a><sup>&#42;</sup> &emsp; <b>&middot;</b> &emsp;
  <a href="https://robamler.github.io" target="_blank">Robert&nbsp;Bamler</a>
  </span>
  <br/>
  <sup>&#42;</sup> denotes equal contribution
  


## About The Project
This is the official GitHub repository for our work [The SVHN Dataset Is Deceptive for Probabilistic Generative Models Due to a Distribution Mismatch](.) where we propose a new split for the SVHN dataset that does not suffer from distribution mismatch.
[**Visit the project page**](https://jzenn.github.io/svhn-remix) and [**download SVHN-Remix**](https://jzenn.github.io/svhn-remix#download) dataset or split.

> The Street View House Numbers (SVHN) dataset [(Netzer et al., 2011)](http://ufldl.stanford.edu/housenumbers/nips2011_housenumbers.pdf) is a popular benchmark dataset in deep learning.
  Originally designed for digit classification tasks, the SVHN dataset has been widely used as a benchmark for various other tasks including generative modeling.
  However, with this work, we aim to warn the community about an issue of the SVHN dataset as a benchmark for generative modeling tasks: we discover that the official split into training set and test set of the SVHN dataset are not drawn from the same distribution.
  We empirically show that this distribution mismatch has little impact on the classification task (which may explain why this issue has not been detected before), but it severely affects the evaluation of probabilistic generative models, such as Variational Autoencoders and diffusion models.
  As a workaround, we propose to mix and re-split the official training and test set when SVHN is used for tasks other than classification.
  We publish a new split and the indices we used to create it at [https://jzenn.github.io/svhn-remix/](https://jzenn.github.io/svhn-remix/).


## Citation:
Following is the Bibtex if you would like to cite our paper :

```bibtex
TBD
```

<p align="right">(<a href="#top">back to top</a>)</p>
