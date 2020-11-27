# Comparasion-of-CNN-RNN-and-HAN-for-Text-Classification-with-Glove-Data-Model
It’s a NLP Problem,the goal of our project is to classify categories of news based on the content of news articles from the BBC website using CNN, RNN and HAN models on two datasets that the former dataset have 2225 news, 5 categories and the latter dataset have 18846 news, 20 categories. 

#Set hyperparameters, such as embedding dimensions of glove model, trainable parameter of  embedding layer, bidirectional LSTM or simple LSTM

#Preprocess the news articles, including removing punctuation ,stopwords, lemmatization,removing outliers in terms of news length and the number of sentences and set the corresponding parameters 

#Tokenize the data using word-index which is fit on the train data,then generate 2D input data (article, word) for CNN and RNN algorithms,and then generate 3D input data (article, sentence, word) for HAN algorithm 

#Use set hyperparameters to build the model architecture and use checkpointing, early stopping to train model, and then compare the test accuracy and validation loss of these three models 

#Utilized:Python,Pandas,Numpy,Seaborn,Matplolib,NLP,DNN,CNN,RNN,HAN,LSTM,GPU,Text Classification,Hyperparameters Tuning
