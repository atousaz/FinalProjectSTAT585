

<!-- badges: start -->
[![travis](https://travis-ci.org/zahrakhoshmanesh/SentiAnalyzer.svg?branch=master)](https://travis-ci.org/zahrakhoshmanesh/SentiAnalyzer)
[![Coverage status](https://codecov.io/gh/zahrakhoshmanesh/SentiAnalyzer/branch/master/graph/badge.svg)](https://codecov.io/github/zahrakhoshmanesh/SentiAnalyzer?branch=master)


<!-- badges: end -->

# SentiAnalyzer
<img src="inst/extdata/SAhexlogo.png" align="right" width="120"/>



### Sentiment analysis for consumer review

SentiAnalyzer is a "one-stop" solution for analysis of of consumer reviews which includes natural language processing (NLP) of consumer sentiments. The dataset that SentiAnalyzer can work with for now is short text and a binary quantification, e.g. whether consumer hits the like button. The NLP of the sentiment is analyzed through the options of algorithms to compile the words and the machinge learning training model of choice.  

## Installation
`install.packages("SentiAnalyzer")`

## Website

[SentiAnalyzer](https://zahrakhoshmanesh.github.io/SentiAnalyzer/)

[Workflow of Functions](https://zahrakhoshmanesh.github.io/SentiAnalyzer/articles/workflow.html)

[What is incide the data: Shiny version](https://joeybudi.shinyapps.io/zahra/)



## Usage
Major steps of processing your textual dataset: 
1. Balancing the dataset

2. Streamlining the text to get a sense of the major keywords

3. Train different classification algorithms(e.g., SVM,NB,RF,KNN,GBM) and choose best parameters for each one to get the highest possible classification accuracy for an specefic dataset

3. Choose the best trained classification algorithm for the specific dataset according to different measures (e.g., FScore, Recall, Precision, Accuracy) 

5. Visualize the output of the confusion matrix, that is, the accuracy of the training model in predicting the sentiment of the consumer review

