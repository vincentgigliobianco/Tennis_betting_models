Tennis betting dataset 

In this project, two models are implemented:

- one first is takes into account the probability that a player wins a match 
- the second one takes into account the probability that the opponent wins the match and also that the first player wins the match

For the first model, the dataset has been shuffled according to the order of columns "losing player" against "winning player"
whereas for the second, the dataset has been created by duplicating rows of each match and inverting the columns of "losing player" against "winning player".

For the second model, the probability of the first player wins and the one that the second model wins are the outputs of the model.
We use the difference of these two probabilities and we call the second model the "winning margin" model.

The datasets have been splitted in train, validation and test sets.

With the hypothesis that :
- we earn same amount of money than the amount initially bet when the prediction of winners is found 
- we lose same amount of money than the amount initially bet when the prediction of winners is not found 

The results shows that the second model "winning margin" is slightly better that the first one