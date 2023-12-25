# Is text preprocessing still worth the time? A comparative survey on the influence of popular preprocessing methods on Transformers and traditional classifiers
This repo contains data and code for our journal article: "Is text preprocessing still worth the time? A comparative survey on the influence of popular preprocessing methods on Transformers and traditional classifiers". 
For a detailed description of our code, please see the article published by Information Systems (Elsevier), by M.Siino et al., 2023.

## Abstract
With the advent of the modern pre-trained Transformers, the text preprocessing has started to be neglected and not specificly addressed in recent NLP literature. However, both from a linguistic and from a computer science point of view, we believe that even when using modern Transformers, text preprocessing can significantly impact on the performance of a classification model. We want to investigate and compare, through this study, how preprocessing impacts on the Text Classification (TC) performance of modern and traditional classification models. We report and discuss the preprocessing techniques found in the literature and their most recent variants or applications to address TC tasks in different domains. In order to assess how much the preprocessing affects classification performance, we apply the three top referenced preprocessing techniques (alone or in combination) to four publicly available datasets from different domains. Then, nine machine learning models - including modern Transformers - get the preprocessed text as input. The results presented show that an educated choice on the text preprocessing strategy to employ should be based on the task as well as on the model considered. Outcomes in this survey show that choosing the best preprocessing technique - in place of the worst - can significantly improve accuracy on the classification (up to 25%, as in the case of an XLNet on the IMDB dataset). In some cases, by means of a suitable preprocessing strategy, even a simple Naïve Bayes classifier proved to outperform (i.e., by 2% in accuracy) the best performing Transformer. We found that Transformers and traditional models exhibit a higher impact of the preprocessing on the TC performance. Our main findings are: (1) also on modern pre-trained language models, preprocessing can affect performance, depending on the datasets and on the preprocessing technique or combination of techniques used, (2) in some cases, using a proper preprocessing strategy, simple models can outperform Transformers on TC tasks, (3) similar classes of models exhibit similar level of sensitivity to text preprocessing.

## Code
All the code used in our experiments can be executed on Google Colab.

## BIBTEX
@article{siino2023is,
title = {Is text preprocessing still worth the time? A comparative survey on the influence of popular preprocessing methods on Transformers and traditional classifiers},
journal = {Information Systems},
pages = {102342},
year = {2023},
issn = {0306-4379},
doi = {https://doi.org/10.1016/j.is.2023.102342},
url = {https://www.sciencedirect.com/science/article/pii/S0306437923001783},
author = {Marco Siino and Ilenia Tinnirello and Marco {La Cascia}}
}

## Useful Links
* [Article PDF](https://www.sciencedirect.com/science/article/pii/S0306437923001783/pdfft?md5=f6a37c2a5b264959fc055b2613fb321e&pid=1-s2.0-S0306437923001783-main.pdf)
* [Official website](https://www.sciencedirect.com/science/article/pii/S0306437923001783) 
