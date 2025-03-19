# Synergistic eigenanalysis of covariance and Hessian matrices for enhanced binary classification on health datasets
Agus Hartoyo, Jan Argasiński, Aleksandra Trenk, Kinga Przybylska, Anna Błasiak, Alessandro Crimi

[Preprint link](https://arxiv.org/abs/2402.09281)

## Abstract

Covariance and Hessian matrices have been analyzed separately in the literature for classification problems. However, integrating these matrices has the potential to enhance their combined power in improving classification performance. We present a novel approach that combines the eigenanalysis of a covariance matrix evaluated on a training set with a Hessian matrix evaluated on a deep learning model to achieve optimal class separability in binary classification tasks. Our approach is substantiated by formal proofs that establish its capability to maximize between-class mean distance (the concept of _separation_) and minimize within-class variances (the concept of _compactness_), which together define the two linear discriminant analysis (LDA) criteria, particularly under ideal data conditions such as isotropy around class means and dominant leading eigenvalues. By projecting data into the combined space of the most relevant eigendirections from both matrices, we achieve optimal class separability as per these LDA criteria. Empirical validation across neural and health datasets consistently supports our theoretical framework and demonstrates that our method outperforms established methods.  Additionally, our approach sheds light on complex DNN decision-making, rendering them comprehensible within a 2D space.

## Source code

The complete source code and datasets for our experiments are accessible through `WBCD dataset experiment`, `Heart disease dataset experiment`, `Neural spike train dataset experiment`, `Pima Indians diabetes dataset experiment`, and `Illustrative case study on WBCD dataset`. These notebooks contain the complete source
code along with the datasets accessed from the same Google Drive account, facilitating easy reproduction and comprehension of our results.
