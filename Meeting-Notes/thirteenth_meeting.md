# What did I achieve

Set up boostrap

Set up navigation at top of page

Set up spinners for long loading functions

Changing index page

Adding navigation for user to easily move between documents

Fixed broken tests

Attempted to set up CI/CD

Created new tests

# Questions

Can I make the repository public if I am using gitignore for the sensitive files?

# discussion

make text bigger compared to photo

different background to make cards stand out

add limit of documents

add button to take you back to start

can make github public

think about the evaluation

I need to think of delpoyment

think of user evaluation

eliminate features and compare 2 groups to see how they work

aim for 8 or 10 minimum people

give them a few documents then say for each of the documents what are the most informative terms for the classifier to make predictions. One of the parts of my system can have the lime summary as well as the text, and the other can jut have the text. My hypothesis would be that if they need to read through the document to find the highlited parts than that would be less efficient and less accurate.

When you are designing your evaluation, you will have a controlled environment where you know the answers to the questions that you are going to ask. and in order to be able to do that you will only use a subset of documents, and depending on what you need out of the documents. We either use documents that have no conspicious data in them. Or if there are documents that could be offensive then just change the text slightly to make them acceptable.

5 sensitive vs 5 non sensitive.

Think about the process and getting the questions right. How are you going to log the results, are you going to setup a logging system. If they select a particular classifier, thigns like that. How are they going to enter the answers to their questions, are they gonna enter it into a system? Would be better if they can just enter it in the system. Allow the user to have input into the system in some way. Have to be clear why the user is using the system for.

You can be asking the user to read the document and either agree or disagree with the clasifier's predictions. or you can ask them to rate whether they think the words are sensitive. Wheter it would be good indication of redaction. Might be better if they can suggest their own redaction. You want input from the user. Either ask them a question or give them a functionality that they can do. Like removing this document from the training set.

don't focus on user uploading document before user study.

The easy option is for them to select which of the classifiers is making the best prediction. Which visualisation is better. we need to see the other classifiers' implemented, we need to see how many documents there are that the classifiers agree and disagree on. for the ones they disagree on, they user can say if it is sensitive or non sensitive. This will allow it to know that which classifier performed best on which document. A classifier could get the prediction wrong but still select important features that the user also agrees on.

is the classifier correct, are the features the classifier decides on correct and does the user agree on.

visualisation is an overall discussion, not a per document thing. For a particular classifier making a particular prediction on a particular document, the terms htat are highlighted by lime can differ from the ones highlited by shap.

What is useful information that the user can give the system. Which of these representations

The purpose of your system is to check whether all the classifiers agree then it is a easy document. however if they disagree then it is a hard document to predict if it is sensitive or not. Therefore, we get a human to predict.

A secondary use of the human is to say which of the identified feature sets, you can have the user rate each of the feature set as to what they think would be most likely related to sensitive information. (shap, lime, lime), that way you can use the features that the user says to reweigh the classifier.

this is one test whitin my user study.

It gives the user the option to view the classifier

designing the user study

what are the tasks that the user are going to do. What are the questions that you are going to ask them? first get them to go throug the documents and agree or disagree with the classifiers and rate the different feature sets Qualitative. Get them to rate the feature sets, some with and without summaries for quantiative data.

Ensure you get feedback on the bits they like and bits they don't like. The other thing is if you're wanting to evaluate a specific component.

Being able to rank feature sets is also part of the production system. If you are asking them in this specific document what is the most important feature for svm.

Ask them how many terms in this document does the classifier think are important for making this classification decision.

For example how long does it take them to respond to a question, how many term features in this document does the classifier think is important. As in count the number of terms highlighted. Having them enter that into the system is not really that important. So think of putting these in an online form.

think about all of these questions and put them into a document, be as specific as you can. The easier it will be to do the evaluation, you will be quicker to identify things that are ambiguous and you will have a clear description of it in your disseration.

allow user to reach end document
