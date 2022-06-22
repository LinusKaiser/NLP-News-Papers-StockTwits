### Short Description

The purpose of this study is to evaluate the most prevalent techniques of natural language processing (NLP) in terms of their advantages and disadvantages for financial sentiment analysis (FSA), as well as to determine whether machine-learning-based approaches to sentiment measurement outperform those that rely on human perception of linguistic features. Additionally, I will outline the differences between these various sentiment analysis techniques by exemplarily showing their application in the financial context to subsequently compare their forecasting performance. To do so, I will use a dataset of messages sent via the online social media website StockTwits as well as a dataset of news headlines. I discover that Machine Learning (ML) improves sentiment classification performance substantially.

### Data Sets
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Wordcloud.png"> StockTwits Data Set - Word Cloud</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Wordcloud.png"> News Headlines Data Set - Word Cloud</img>
    </div>
</div>

### Processing Pipeline
<img src="Outputs/Pipeline.png" class="center"></img>


### Results
#### Dictionaries
#### Harvard-IV
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/StockTwits - Harvard-IV - none.png"></img>
        <span class="caption">StockTwits - Harvard-IV - Confusion Matrix</span>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/News Headlines - Harvard-IV - none.png"></img>
        <span class="caption">News Headlines - Harvard-IV - Confusion Matrix</span>
    </div>
</div>

#### Loughran and McDonald
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/StockTwits - Lo&Mc - none.png"> StockTwits - Loughran and McDonald - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/News Headlines - Lo&Mc - none.png"> News Headlines - Loughran and McDonald - Confusion Matrix</img>
    </div>
</div>

#### Machine Learning
#### Naive Bayes
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Naive Bayes.png"> StockTwits - Naive Bayes - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Naive Bayes.png"> News Headlines - Naive Bayes - Confusion Matrix</img>
    </div>
</div>

#### Support Vector Machine
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Support Vector Machine.png"> StockTwits - Support Vector Machine - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Support Vector Machine.png"> News Headlines - Support Vector Machine - Confusion Matrix</img>
    </div>
</div>

#### Logistic Regression
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Logistic Regression.png"> StockTwits - Logistic Regression - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Logistic Regression.png"> News Headlines - Logistic Regression - Confusion Matrix</img>
    </div>
</div>

#### Multilayer Perceptron
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Multilayer Perceptron.png"> StockTwits - Multilayer Perceptron - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Multilayer Perceptron.png"> News Headlines - Multilayer Perceptron - Confusion Matrix</img>
    </div>
</div>

#### Multilayer Perceptron
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Multilayer Perceptron.png"> StockTwits - Multilayer Perceptron - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Multilayer Perceptron.png"> News Headlines - Multilayer Perceptron - Confusion Matrix</img>
    </div>
</div>

#### Neural Network
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Neural Network.png"> StockTwits - Neural Network - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Neural Network.png"> News Headlines - Neural Network - Confusion Matrix</img>
    </div>
</div>

<style>
    .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
    }
</style>
