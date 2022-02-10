# wordle

This is a solver for wordle game.

Entropy is calculated for each choice and the highest information gain option is the optimal choice.
And the wordlist is filtered after each answer.

The source dictionary, however, may or may not be the optimal choice - there might be too many irrelavant 'words', and at the same time some words can be missing. 
