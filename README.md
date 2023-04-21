# Word-Embedding
The code above is a Python script that demonstrates how to create Word Embeddings using the gensim library. Word Embedding is a popular technique in Natural Language Processing that allows words to be represented as vectors in a high-dimensional space.

In this example, the data is first tokenized and then the stop words are removed. The code then trains two models: one using the Continuous Bag-of-Words (CBOW) algorithm and the other using the Skip-Gram algorithm. Both models are trained on the preprocessed sentences using the Word2Vec function from the gensim library.

After the models are trained, the script gets the word embeddings for a specific word by calling the 'wv' attribute of the models and providing the word as the argument. The output will be a vector representation of the word in a 50-dimensional space.

Finally, the script uses the 'print' function to output the word embedding for the word 'ung' using the CBOW model. The 'nltk' library is also used to download the 'punkt' package which is needed for tokenization.

This code can be useful for those who want to experiment with Word Embeddings and learn how to train their own models using Python and gensim.
