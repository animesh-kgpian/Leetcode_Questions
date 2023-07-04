# TF-IDF-implimentation
TF-IDF (Term Frequency-Inverse Document Frequency) is a way of measuring how relevant a word is to a document in a collection of documents.
This is done by multiplying two metrics:

Term Frequency (TF): how many times a word appears in a document.
Inverse Document Frequency (IDF): the inverse document frequency of the word across a collection of documents. Rare words have high scores, common words have low scores.

TF-IDF has many uses, such as in information retrieval, text analysis, keyword extraction, and as a way of obtaining numeric features from text for machine learning algorithms.

#formula
TF(word, document) = “number of occurrences of the word in the document” / “number of words in the document”
IDF(word) = log(number of documents / number of documents that contain the word)
TF-IDF(word, document) = TF(word, document) * IDF(word)


#The use of TF-IDF in Machine Learning
TF-IDF is often used to transform text into a vector of numbers, otherwise known as text vectorization, where the numbers of the vectors are meant to somehow represent the content of the text.

TF-IDF gives us a way to associate each word in a document with a number that represents how relevant each word is in that document. Such numbers can be then used as features of machine learning models.
