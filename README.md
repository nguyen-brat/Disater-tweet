# Disater-tweet  
https://www.kaggle.com/competitions/nlp-getting-started
# **Detect the tweet is about desater of not**
**my code reach 0.827 accuracy and rank 139/713**
![Screenshot 2022-08-12 100603](https://user-images.githubusercontent.com/95292664/184277524-9b3f59d0-eed3-4295-a52f-00bbb103fe3a.png)

**preprocess data**

1. detele the link in the tweet
2. tokenize 1500 most common word
3. convert in to tf.Dataset and split the data
4. choosing the LSTM model and BERT model to try (BERT model reach better accuracy)
