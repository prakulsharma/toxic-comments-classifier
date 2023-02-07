# Toxic Comments Classifier

This notebook's motivation is to create a ready-to-made all-in-one-place of NLP preprocessing and feature extraction techniques and codes. Furthermore, as we would not use all of those techniques simultaneously as it would depend on different specific NLP problems, each task was design as a separate module with its quick and straightforward explanation, then the implementation that we could pick out, plug-and-play independently and conveniently. We will mainly use the [Real or Not? NLP with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started) dataset for illustration and other dataset such as [Jigsaw Multilingual Toxic Comment Classification](https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification), and [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) for some specific tasks too.


# Virtual Environment Setup
-   Create virtual environment

        mkvirtualenv -p `which python3.6` toxic-comments-classifier
 

-   Install dependencies: 
    
        pip install -r requirements.txt 
