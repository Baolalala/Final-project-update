# Sentiment analysis of app reviews for requirements engineering

The project aims to develop an automatic classification system that can identify positive and negative sentiment in app reviews.

## Description

In today's digital era, customer feedback is an essential aspect of any business. With the exponential growth of app stores, online reviews have become a critical component of the decision-making process for potential customers. The sentiment of these reviews can significantly impact the success of an application. Thus, sentiment analysis has become a crucial tool in natural language processing (NLP) to extract insights from customer feedback.

Various models have been developed to perform sentiment analysis, including Support Vector Machines (SVMs), Bidirectional Encoder Representations from Transformers (BERT), Robustly Optimized BERT approach (RoBERTa), BERT with Recurrent Neural Networks (RNNs), and BERT with Long Short-Term Memory (LSTM). While SVMs are a widely used baseline model for sentiment analysis, more advanced models like BERT and its variants have recently shown superior performance in a variety of NLP tasks.

In this project, we aim to compare the performance of these five models in sentiment analysis of app reviews. We will use a dataset consisting of positive and negative reviews, and each model will be trained and evaluated using various performance metrics. The project will provide insights into the effectiveness of advanced models in sentiment analysis and their potential benefits over traditional models.

By comparing the performance of SVM, BERT, RoBERTa, BERT with RNN, and BERT with LSTM models in sentiment analysis of app reviews, this project will shed light on the effectiveness of advanced models and their potential benefits over traditional models.

## Getting Started

### Dependencies

* Windows system with 2080Ti GPU (at least)
* PyTorch  1.8.1 Python  3.8(ubuntu18.04) Cuda  11.1
* Jupyter lab or Jupyter notebook needed
* Library needed as follow
```
!pip install scikit-learn=='0.24.2'
!pip install transformers
!pip install torch
!pip install numpy
!pip install seaborn
!pip install pandas
!pip install tqdm
!pip install collections
!pip install matplotlib
```

### Installing

* Just down load the folder 

### Executing program

* On MacOs, open terminal and type ``` jupyter lab ```
* On Windows. First download anaconda, https://www.anaconda.com/products/distribution then, open anaconda terminal and type ``` jupyter lab ```
* In jupyter lab, open the folder download and open one of five ipynb file which represent 5 different sentiment analysis models.
* Finally, select ``` Run all cells ```
* If you want to simply test one sentence then you can scroll down to the end of code and edit the sentence I gave ``` the food was delicious but it was spicy ```
* Re-run the code cell will give you the result of the especific sentence

## Help

If use MacOs with M1 chip to run the code, the code may have problem when running.
My solution is to use a Windows-based computer with at least 2080Ti GPU to run the code.

## Authors

ex. Yinan Yan  
ex. [@tintimsse](https://twitter.com/tintimsse)

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Acknowledgments

* Liping Zhao (my superviser)
