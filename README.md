# A-deep-learning-based-investigation-of-the-impact-of-genetic-variants-on-chromatin-accessibility

This repository contains the code I wrote for my homonimous project course. 

The data and model that were used are not publicly available.

Project abstract: 

Understanding the determinants of transcriptional regulatory elements and the mechanisms through which disease-associated genetic variants disrupt their activities remains an open
challenge. Recent attempts at functionally annotating the noncoding genome employ complex models, such as deep convolutional neural networks (CNNs). Although these models can be incredibly accurate in their predictions, they are becoming increasingly notorious for their lack of interpretability. In trying to surpass their black-box
nature, so-called feature attribution methods have emerged. In this project, the outcome of two such methods when applied to a CNN that predicts cell type-specific chromatin accessibility regions are compared, and their potential to evaluate the impact of genetic variants on chromatin accessibility is discussed, offering insights into future steps to further address the interpretability issues of deep neural networks in the field of genomics.


In the notebook pred_fulldataset.ipynb, I learned how to load the model, one-hot-encode the sequences and obtain the predictions. Summary statistics of the model's performance are also included. 

The notebook mutagenesis.ipynb contains the main functions used in this project to implement the feature attribution method known as in-silico saturation mutagenesis, as well as the results of the comparison of the two feature attribution methods. 

