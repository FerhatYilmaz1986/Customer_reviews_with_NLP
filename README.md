# Natural Language Processing(NLP) :  
## Definition :  
NLP is a way of computers to understand, interpret and manipulate human language.  
## Components Of NLP :   
-   Morphological and Lexical Analysis
-   Syntactic Analysis
-   Semantic Analysis
-   Discourse Integration
-   Pragmatic Analysis  
## Text Processing :  
-   Word extraction  
-   Stopwords removal  
-   Stemming/Lemmatization  
-   Frequency counts / TF-IDF (Representation)  
## Producing word embeddings  
  ### Word Embeddings:  
  When working with text in machine learning models, we need to convert strings into numbers in order to do calculations  
  with them.One-hot representation is not a good representation of words because it is very sparse.  
  Using the Embedding layer creates a dense representation of the vectors.  
  Word embeddings provides an efficient way by representing similar words with similar numbers/vectors. Idea is clustering  
  words having similar sentiment together in a multi-dimensional space. It prevents having sparse matrix with huge number  
  of features to represent text data. For example, with word embedding, word 'dog' has a specific n dimensional vector  
  representing it. The word 'husky' is going to have a very similar vector to the vector of 'dog', showing semantic  
  distance between these two words. 
    
  ![Word Embeddings](/images/word2vec.png)  
  #### Definition of embedding in google glossary :  
  A categorical feature represented as a continuous-valued feature. Typically, an embedding is a translation of a high-dimensional vector   into a low-dimensional space    
## NLP with Deep learning using Tensorflow/Keras  
 ![NLP with deep learning](/images/deeplearning.png)  
 *[NLP with Keras Notebook using Subwords(Pre-tokenized dataset)](/NLP_Tf_Keras.ipynb)  
## Text Classification using NLTK  
NLTK stands for Natural Language Tool Kit.It is a tool for teaching, and working in, computational linguistics using Python.  
  
  *[Text Classification Notebook](/NLTK.ipynb)  
### Text Classification Applications :  
-   Recommending  
-   Spam filtering  
-   Personalized news  
-   Email routing  
-   Email prioritizing  
### Required processes :  
-   Word extraction tools  
-   Document representation  
-   Dimensionality reduction  
-   Classifier model  
-   Semantic representation  
## References  
 -  [Scikit-learn documentation](https://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html)  
 -  [Tensorflow documentation](https://www.tensorflow.org/tutorials/text/word_embeddings)  
 -  [Wikipedia](https://en.wikipedia.org/wiki/Natural_language_processing) 
 -  [NLTK documentation](https://www.nltk.org/) 
    
