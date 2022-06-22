<div>
### **Short Description**

The purpose of this study is to evaluate the most prevalent techniques of natural language processing (NLP) in terms of their advantages and disadvantages for financial sentiment analysis (FSA), as well as to determine whether machine-learning-based approaches to sentiment measurement outperform those that rely on human perception of linguistic features. Additionally, I will outline the differences between these various sentiment analysis techniques by exemplarily showing their application in the financial context to subsequently compare their forecasting performance. To do so, I will use a dataset of messages sent via the online social media website StockTwits as well as a dataset of news headlines. I discover that Machine Learning (ML) improves sentiment classification performance substantially.

### **Data Sets**
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Wordcloud.png"> StockTwits Data Set - Word Cloud</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Wordcloud.png"> News Headlines Data Set - Word Cloud</img>
    </div>
</div>

### **Processing Pipeline**
<img src="Outputs/Pipeline.png" class="center"></img>


### **Results**
#### **Dictionaries**
#### <u>Harvard-IV</u>
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

#### <u>Loughran and McDonald</u>
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/StockTwits - Lo&Mc - none.png"> StockTwits - Loughran and McDonald - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/Dictionaries/News Headlines - Lo&Mc - none.png"> News Headlines - Loughran and McDonald - Confusion Matrix</img>
    </div>
</div>

#### **Machine Learning**
#### <u>Naive Bayes</u>
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Naive Bayes.png"> StockTwits - Naive Bayes - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Naive Bayes.png"> News Headlines - Naive Bayes - Confusion Matrix</img>
    </div>
</div>

#### <u>Support Vector Machine</u>
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Support Vector Machine.png"> StockTwits - Support Vector Machine - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Support Vector Machine.png"> News Headlines - Support Vector Machine - Confusion Matrix</img>
    </div>
</div>

#### <u>Logistic Regression</u>
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Logistic Regression.png"> StockTwits - Logistic Regression - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Logistic Regression.png"> News Headlines - Logistic Regression - Confusion Matrix</img>
    </div>
</div>

#### <u>Multilayer Perceptron</u>
<div class="row">
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Multilayer Perceptron.png"> StockTwits - Multilayer Perceptron - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Multilayer Perceptron.png"> News Headlines - Multilayer Perceptron - Confusion Matrix</img>
    </div>
</div>


<div class="row">
<h3>#### <u>Neural Network</u> </h3>
    <div class="column">
        <img src="Outputs/Graphs/StockTwits - Neural Network.png"> StockTwits - Neural Network - Confusion Matrix</img>
    </div>
    <div class="column">
        <img src="Outputs/Graphs/News Headlines - Neural Network.png"> News Headlines - Neural Network - Confusion Matrix</img>
    </div>
</div>
</div>


<svg fill="none" viewBox="0 0 400 400" width="400" height="400" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
        <div xmlns="http://www.w3.org/1999/xhtml">
            <style>
            h3 {
                color: LightBlue;
            }

            .center {
                display: block;
                margin-left: auto;
                margin-right: auto;
                width: 50%;
            }

            .img-with-text {
                text-align: justify;
                width: [width of img];
            }

            .img-with-text img {
                display: block;
                margin: 0 auto;
            }

            .column {
            float: left;
            width: 45%;
            padding: 17px;
            }

            .row::after {
            content: "";
            clear: both;
            display: table;
            margin-bottom:50px;
            }

            </style>
        </div>
    </foreignObject>
</svg>