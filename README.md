It was attempted to train a BERT model in the task of sentiment analysis, with Stanford's IMDB Dataset. Specifically, the "distilbert-base-uncased" model from Hugging Face was used. 

Also, the training and testing folders were used from the IMDB dataset, containing 50,000 reviews, of which 25,000 are positive and 25,000 are negative. The split for training/validation/test set was 80:10:10. 

DistilBERT is a much smaller model than classical BERT, with 66m parameters, and 6 transformer layers, compared to BERT's 110m parameters and 12 transformer layers. It performs at about 97% of BERT while being 40% of its size.
