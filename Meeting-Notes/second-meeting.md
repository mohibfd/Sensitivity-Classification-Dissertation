# What did I achieve:

Read the two papers discussing sensitivity classifiers

looked at most suitable web framework for backend (Leaning towards Flask)

looked at gensim, spacy, mpld3, lime, textblob, scikit-learn

read articles about e-discovery with nlp

Created initial MoSCoW method.
Must have: Classifier for sensitive data; visiualization as to why the model decided sensitive or non sensitive; high level of security.

Shoud have: Good user interface for optimal user experience; High speed when running different actions in the website that way the user does not have to wait; user gets feedback as to how their response improves the model

Could have: Create new state of the art model that beats previous best model; user input telling the model whether it is correct or incorrect to improve the model further

Will not have: unsure at this stage, will update later

Created wireframe for website (https://www.figma.com/file/2qQgHB1fgEhSeKYf2WanMz/Level-4-Project?node-id=0%3A1)

Read papers about model explanation

found SHAP which is a python library similar to LIME

# Questions:

The project lecture advised to not write code for anything that will not benefit the dissertation. I am a bit unsure what that means

Is my MoSCoW method accurate or does it need changing?

Is there anything that needs changing in the wireframe that I created?

Should I attempt to start creating the model or should I research more?

# Future plans:

Start building the model by utilizing some of the frameworks and libraries discussed. The plan is to set the foundation of the model.

continue on what you are doing and keep developing the moscow requirements, think about the big vision and what we've talked today. keep developing your wireframe and next week we will have a further developed vision of the project. What direction do you want to go? Try and get more detail into your moscow requirement. Run basic things like lime and shap so you produce feature importance scores for it. If you do that then by next week we can start really thinking about the frontend, what visualisations do we want to put into the frontend. How can you combine different visualisation libraries to

These feature importance techniques typically look at term feature, it must be an itneresting avenue to go down what about other features. What would be a reasonable way to visualise the importance of different word embedding features.

# discussion in meeting:

need graphics that easily convey important information about the classifier

must haves are: easily provide user with information that user cannot get without my system

Should haves: icing on the cake

could have: learn from what we've done combining these approaches and try to integrate it into a single model

this is looking at an individual document, as well as this user might want to look at statistics of overall documents.

Look at cluster of terms in sensitive and not sensitive, general stats on the collection level. Don't forget plots and visualisations.

Look at different approaches and what terms they think are most important. Provide feedback and reweight term feature importance value. Classifier should reweight importance of the term that the user decides is either sensitive or not. My feature importance model should reflect

send message on monday for data
