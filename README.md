# Sentiment-Analysis-using-a-pre-trained-model
The main goal of this project was to perform sentiment analysis on a movie review dataset using a pre-trained model. The dataset consisted of 50,000 movie reviews, which were evenly split into 25,000 for training and 25,000 for testing.

We started by preprocessing the data, which involved tokenizing the text, converting it to lowercase, and removing stop words and punctuations. We then converted the data into a format suitable for training our model.

Next, we used a pre-trained model, DistilBERT uncased, to train our sentiment analysis model. We used the Hugging Face Transformers library to load the pre-trained model and fine-tune it on our movie review dataset. We trained the model for 3 epochs with a batch size of 16.

After training the model, we evaluated its performance on the test dataset. We computed the loss and accuracy scores, which were 0.2129 and 0.9261, respectively. We also used the predicted sentiment labels to generate a classification report and confusion matrix to visualize the model's performance on each sentiment label.

In conclusion, we successfully performed sentiment analysis on a movie review dataset using a pre-trained model. The model achieved high accuracy and performed well on each sentiment label.
