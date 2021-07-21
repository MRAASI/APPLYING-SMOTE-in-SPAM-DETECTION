#  Synthetic Minority Oversampling Technique or SMOTE 
Imbalanced classification involves developing predictive models on classification datasets that have a severe class imbalance.

The challenge of working with imbalanced datasets is that most machine learning techniques will ignore, and in turn have poor performance on, the minority class, although typically it is performance on the minority class that is most important.

One approach to addressing imbalanced datasets is to oversample the minority class. The simplest approach involves duplicating examples in the minority class, although these examples don’t add any new information to the model. Instead, new examples can be synthesized from the existing examples. 
	
A scatter plot of the dataset is created showing the large mass of points that belong to the majority class (blue) and a small number of points spread out for the minority class (orange). We can see some measure of overlap between the two classes.Counter({0: 9900, 1: 100})
	
![image](https://user-images.githubusercontent.com/46440771/126461459-8459a45d-47ab-4fff-bf0a-43fb73d66e4a.png)

Finally, a scatter plot of the transformed dataset is created.

It shows many more examples in the minority class created along the lines between the original examples in the minority class.

![image](https://user-images.githubusercontent.com/46440771/126461776-7081c3a5-83b9-4e5a-9a51-b1448ad0188f.png)


# Applying SMOTE Technique in SPAM MESSAGE DETECTION

In this project we used text classification to determined whether the message is spam or not.  NLP methods are used to prepare and clean the text data (tokenization, remove stop words, stemming) and used different machine learning algorithms to get more accurate predictions. The following classification algorithms have been used: Logistic Regression, Naive Bayes, Support Vector Machine (SVM), Random Forest.

In today's internet-oriented data; receiving spam  messages are quite obvious. Most of the time such messages  are commercial. But many times,  may contain some phishing links that have malware. This arises the need for proposing prudent mechanism to detect or identify such spam messages so that time and memory space of the system can be saved up to a great extentIt provides the notification for the given message as spam if it is spam message.
Dataset Source: https://www.kaggle.com/uciml/sms-spam-collection-dataset
Base paper source: https://scihubtw.tw/10.1109/ICCMC48092.2020.ICCMC-000177
