# Working with NLP methods creating Featurization Algo from Scratch

##Featurization & why it's required

Featurization is the process to convert varied forms of data to numerical data which can be used for basic ML algorithms. Data can be text data, images, videos, graphs, various database tables, time-series, categorical features, etc.
By applying featurization techniques, one can convert the data to numerical features to feed that data to the ML model.
There are various featurization techniques that are used. The technique depends on data type and sometimes on the application domain. 

Here we're discussing about some of the basic featurization techniques used for text data

Featurization for the text data

#### What does tf-idf mean?
Tf-idf stands for term frequency-inverse document frequency, and the tf-idf weight is a weight often used in information retrieval and text mining. This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus. The importance increases proportionally to the number of times a word appears in the document but is offset by the frequency of the word in the corpus. Variations of the tf-idf weighting scheme are often used by search engines as a central tool in scoring and ranking a document's relevance given a user query. 
One of the simplest ranking functions is computed by summing the tf-idf for each query term; many more sophisticated ranking functions are variants of this simple model. 
Tf-idf can be successfully used for stop-words filtering in various subject fields including text summarization and classification. 

TF-IDF = Term Frequency (TF) * Inverse Document Frequency (IDF)

Term Frequency = Term Frequency, which measures how frequently a term occurs in a document.Considering the variation in word's occurence due
to document length there arises a need for Normalization

Thus, the term frequency is often divided by the document length (aka. the total number of terms in the document) as a way of normalization:


    tf(t,d) = Frequency of the term in the document / the total no of words in that document





