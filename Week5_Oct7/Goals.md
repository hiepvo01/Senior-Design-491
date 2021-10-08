Personal and Group projects on applying NLP models on data of interest or software documentation data

# Notes for Improvements
- Observe can comments carefully on how each data cleaning step can affect the quality of data
- Try different feature extraction models other than tf-idf and NLTK for comparison (Stanford NLP, Spacy, Glove)
- To detect phrases within a single word or sentence, try apply gensim's [Phrases model](https://radimrehurek.com/gensim/models/phrases.html)
- There is also a [Doc2Vec model](https://radimrehurek.com/gensim/models/doc2vec.html) that let you train whole document data with or without single word vectors if you want to find similar files as a whole instead of just similar words
- Try new evaluation methods that focus on POS tags instead of existing categories: cluster words base on their tags, check if similar words are also the same tag or synonym, check how many words in the Noun cluster are actually Noun, etc... These evaluations would very beneficial to our final project
- Compare predicted similar words by both meaning, pos tag and their vectors ([Cosine Similarity](https://www.delftstack.com/howto/python/cosine-similarity-between-lists-python/))
- Keep on exploring and learn to implement new models so that the group would have a more variety when working together as a whole.

- On a side note if someone wants to know about handling emoji in text data, this [article](https://medium.com/geekculture/text-preprocessing-how-to-handle-emoji-emoticon-641bbfa6e9e7) can help