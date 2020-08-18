## Nepalese-News-Classifier-with-word2vec-model-integration

In this project, we scraped articles from several online Nepali news portals. Then, we experimented the dateset on different Machine learning classifiers.
In next phase, we trained word2vec model on the training set of corpus and took sum of individual tokens to generate vector embedding of testing corpus. Then, we build a simple news recommendataion engine that recommended news with closest euclidean distance

Possible Improvements for the Classifier:
* Use Language Model Pretrained on huge Nepalese Corpus
* Hierarchical Attention Network Architecture

Possible Improvements for the generating word2vec based document embedding
* Use weighted sum based on factors like IDF weights of tokens
* Encoder layer of Pretrained Language Models

### Dependencies
1. pandas
2. codecs
3. numpy
4. pickle
5. sklearn
6. gensim
7. python 3+ to support unicode 
goodNewsData.tar.gz contains csv file where each row contains a single Nepalese news article.

### STEPS TO RUN THE CODE
1) Download all the files.
2) Extract goodNewsData.tar.gz and trainedModel.tar.gz in same directory as the
ipynb code is located
3) first run trainOnModels.ipynb to train the word2vec model.Or you can use the trained model , trainedModel.tar.gz after extracting it
4) Now you can run other ipynbs as well. 
