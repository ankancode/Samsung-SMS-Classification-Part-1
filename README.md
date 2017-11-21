# Samsung-SMS-Classification-Part-1

Classfication Classes - Spam, Ham, Info

First I performed feature engineering on the dataset,

- Replaced DATE,TIME,DIGITS,ALPHANUMERNIC and Hyperlink.
- Removed punctuation
- Peformed lemmatization and stemming on the dataset
- Removed Non-English words from the dataset.\
- Peformed Tokenization

Finally used Support Vector Classifier for modelling on the processed data

I used NLTK and Sklearn packages of Python for this challenge. I got a accuracy of 93.77% on the final test data.
