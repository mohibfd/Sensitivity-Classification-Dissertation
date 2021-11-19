# What did I achieve:

made distilBERt work with lime on only 500 characters for every document

got distilBERT to work with all characters of the documents seperated into different sections but only on 5% of the entire data

managed to get up to 10% of the data after changing the ram

read about toBERT to try and fix my issue

tried (longformer) long transformer

tried longRoBERTa

managed to get longformer working on the dataset but it has a bad f1 score and haven't tested it on lime yet

# future data

don't normalise test data

randomly remove sensitive documents from your evaluation set so that the distribution is roughly 90% non sensitive and 10% sensitive and then apply my classifier to it again and see how the f1 score is

give bert an other shot

what is lime actually predicting?
