Texts are complex dataset which contains variaties of symbols and variable sizes. However, from our human's perspectives, 
the structure type of a text can be divided into four levels like article, paragraph, sentence, word, namely a long text 
consists of paragraphs, and a paragraph consists of a series of sentences, and a sentence consists of sequences of words.

For texts of variable sizes, it is not proper to consider them only as sequences of words. Instead, we can re-organize 
them into hierarchical structure such as paragraphs, sentences and words.

This min-project attempts to test the performances of hierarchical structure in Recurrent Neural Network model. That is, 
First we use RNN model to go over sequences of words in a sentence to obtain a sentence vector, then use another RNN model
to transform sentence vectors into a text vector.