# Task_3

First I used 4 classical Machine learning models.
the pipeline of the training was tokenization of the words and then using TfIdf then train the model.
tokenization of the data included removing stop words.
the first model was Decision Tree Classifier, it horribly overfitted the data.
the second model was Naive Bayes model which gave the best accuracy.
the last two models were SVM and Random Forest Classifier, they didn't give the best results.
then I used a deep learning model.
first tokenized the data then padding it.
I used the Bidirectional LSTMs model with 256 units hen 1 FC layer of 1024 units.
I used checkpoints to monitor the best weights for the validation split.
the model was overfitting so I decreased batch size and number of epochs and added dropout layers.

