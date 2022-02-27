#Approaches for Sentiment Analysis
1.	Simple Multinomial Naïve Bayes Model.
2.	RNN with LSTM layer
3.	Bidirectional RNN
4.	XLNet pretrained model
5.	Data Augmentation using niacin to improve the model

#Ways to improve the accuracy of the model:

1.	Easy Data Augmentation, I used niacin library to do EDA which includes synonym replacement and random swap.

2.	Use different RNN architecture (bidirectional RNN)

3.	Add more LSTM layer to RNN

4.	Eliminate stopwords

5.	Use different word embedding method

6.	Using pretrained word embeddings instead of having our word embeddings randomly. We get these vectors simply by specifying which vectors we want and passing it as an argument to build_vocab.
