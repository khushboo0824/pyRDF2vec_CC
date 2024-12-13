RDF2Vec is an unsupervised technique that builds further on Word2Vec, where an embedding is learned per word, in two ways:

the word based on its context: Continuous Bag-of-Words (CBOW);

the context based on a word: Skip-Gram (SG).

To create this embedding, RDF2Vec first creates “sentences” which can be fed to Word2Vec by extracting walks of a certain depth from a Knowledge Graph.
this Repository contains an implementation of RDF2VEC
