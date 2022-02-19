# What I achieved

Created balanced LSTM (it was biased towards classifying all documents as non-sensitive)

Set up Cross validation for LSTM

Fixed pickling issues with LSTM

Fully implemented LSTM into the app with LIME and SHAP. However, turns out ELI5 is unable to make explanations for textual deep learning models, only images. Therefore, LSTM only has LIME as available visualisation

Currently writing draft for user study plan

# Questions

Aren't users unable to look at overall explanations since it shows sensitive data?

# Discussion

show text without highlighting

show eli5 for both LR and XGB

does this documment contain any personal information? Does it discuss anybody's personal information?

move the squares around so that your top left hand corner is the overall information, switch with bottom right

move bottom left to top right.

depending on the classifier's predictions where does it go?

Sensitive and non sensitive is where they do their tasks in.

The other two can be used as a secondary filter to make it easier to see documents that any classifier says are sensitive or non sens

So the disagreements are in the Sens and NOn sens explanations

any document that any classifier says is sensitive goes there
and vice versa for the other
