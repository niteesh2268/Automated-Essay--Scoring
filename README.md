# Automated Essay Scoring
> A Deep Learning model that predicts the score of a given input essay. 

The dataset is from Kaggle ASAP competition which was provided by The Hewlett Foundation.


### Performance
The accuracy is calculated by **Quadratic Weighted Kappa(QWK)**, which measures the agreement between two raters. The model architecture consists of 2 Long Short Term Memory(LSTM) layers with a Dense output layer. The final layer uses the Relu activation function. The QWK is calculated by training model on the dataset using 5-Fold Cross Validation and taking the average for all five folds.


## References
1. [A Neural Approach to Automated Essay Scoring](http://aclweb.org/anthology/D/D16/D16-1193.pdf) </br>
2. [Automatic Text Scoring Using Neural Networks](https://arxiv.org/pdf/1606.04289.pdf)
