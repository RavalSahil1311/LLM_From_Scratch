# LLM From Scratch

- [Dataset](/Wizard_of_OZ.txt) used to train Bigram Language Model

## Bigram Language Model

A bigram language model is a statistical language model used in natural language processing (NLP) and computational linguistics to predict the likelihood of a word based on the preceding word. Specifically, it models the probability of each word in a sequence given the word that precedes it.

In a bigram language model, the probability of a word `w_i` given its preceding word `w_{i-1}` is estimated using the formula:

\[ P(w_i | w_{i-1}) = \frac{Count(w_{i-1}, w_i)}{Count(w_{i-1})} \]

Where:
- `Count(w_{i-1}, w_i)` is the number of occurrences of the bigram `(w_{i-1}, w_i)` in the training corpus.
- `Count(w_{i-1})` is the total number of occurrences of the word `w_{i-1}` in the training corpus.

In simpler terms, the bigram model calculates the probability of a word occurring given the word that comes just before it. This model assumes that the probability of a word depends only on the preceding word.