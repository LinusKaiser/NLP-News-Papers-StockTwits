#
### **Short Description**

The purpose of this study is to evaluate the most prevalent techniques of natural language processing (NLP) in terms of their advantages and disadvantages for financial sentiment analysis (FSA), as well as to determine whether machine-learning-based approaches to sentiment measurement outperform those that rely on human perception of linguistic features. Additionally, I will outline the differences between these various sentiment analysis techniques by exemplarily showing their application in the financial context to subsequently compare their forecasting performance. To do so, I will use a dataset of messages sent via the online social media website StockTwits as well as a dataset of news headlines. I discover that Machine Learning (ML) improves sentiment classification performance substantially.

#

### **Data Sets**

| StockTwits Word Cloud   |  News Headlines Word Cloud|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-Wordcloud.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-Wordcloud.png)


#
### **Processing Pipeline**
![Image](/Outputs/Pipeline.png "Processing Pipeline")
#

### **Results**
#
#### **Dictionaries**
#### <u>Harvard-IV</u>

| StockTwits Harvard-IV Dictionary   |  News Headlines Harvard-IV Dictionary|
| ------------- | ------------- |
![Image](/Outputs/Graphs/Dictionaries/StockTwits-Harvard-IV.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/Dictionaries/NewsHeadlines-Harvard-IV.png)
|Accuracy:  0.5230523690773067|Accuracy:  0.5721745635910225|

#### <u>Loughran and McDonald</u>
| StockTwits Loughran & McDonald Dictionary   |  News Headlines Loughran & McDonald Dictionary|
| ------------- | ------------- |
![Image](/Outputs/Graphs/Dictionaries/StockTwits-Lo&Mc.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/Dictionaries/NewsHeadlines-Lo&Mc.png)
|Accuracy:  0.5375361596009975|Accuracy:  0.5841845386533666|

#
#### **Machine Learning**
#
#### <u>Naive Bayes</u>
| StockTwits Naive Bayes   |  News Headlines Naive Bayes|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-NaiveBayes.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-NaiveBayes.png)
|Accuracy: 0.7785857246253798|Accuracy: 0.7737062296905709|
|8 min 42.6 sec|3 Min 20.8 sec|

#### <u>Support Vector Machine</u>
| StockTwits Support Vector Machine   |  News Headlines Support Vector Machine|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-SupportVectorMachine.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-SupportVectorMachine.png)
|Accuracy: 0.6277|Accuracy: 0.6901|
|79 min 28.9 sec|57 min 23.9 sec|


#### <u>Logistic Regression</u>
| StockTwits Logistic Regression   |  News Headlines Logistic Regression|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-LogisticRegression.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-LogisticRegression.png)
|Accuracy: 0.8244248523230233|Accuracy: 0.7961816070591451|
|5 min 35.4 sec| 2min 10 sec|


#### <u>Multilayer Perceptron</u>
| StockTwits Multilayer Perceptron   |  News Headlines Multilayer Perceptron|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-MultilayerPerceptron.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-MultilayerPerceptron.png)
|Accuracy: 0.8085178475501894|Accuracy: 0.7768529795204634|
|8 min 25.4 sec|3 min 9.7 sec|


#### <u>Neural Network</u>
| StockTwits Neural Network   |  News Headlines Neural Network|
| ------------- | ------------- |
![Image](/Outputs/Graphs/StockTwits-NeuralNetwork.png "StockTwits Data Set - Word Cloud") | ![News Headlines Data Set - Word Cloud](/Outputs/Graphs/NewsHeadlines-NeuralNetwork.png)
|Accuracy: 0.830794497488041|Accuracy: 0.7621|
|63 min 48.3 sec|58 min 24.7 sec|


