# Questions Group 1

1. We have questions about WSDModel_approach1 and WSDModel_approach2. We understand them conceptually, but are not sure what the two implementations should look like. For approach 1: how can we predict the word sense based on the word's index? For approach 2: how can we predict the word sense based on the final hidden state and do we access it with predicted_sense[:,-1]?

2. We are not sure how to use the different FIELDS in our model. Currently, we only use wordsense (column 2) and context (column 4).

3. Could you take a look at our code (the model and the training) and see if it's correct for approach 2?