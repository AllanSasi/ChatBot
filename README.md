# ChatBot
Simple python chatbot

# NLP
NLP is a way for computers to analyze, understand, and derive meaning from human language in a smart and useful way. By utilizing NLP, developers can organize and structure knowledge to perform tasks such as automatic summarization, translation, named entity recognition, relationship extraction, sentiment analysis, speech recognition, and topic segmentation.

# NLTK
Natural Language Toolkit is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries.
Natural Language Processing with Python provides a practical introduction to programming for language processing.

- Issue with text-data is that its all in text format, i.e. strings.
In order to perform the task, Machine learning algorithms need some sort of numerical feature vector. So, before starting with any NLP project we need to pre-process it .

# Basic text pre-processing includes:
- Converting the entire text into uppercase or lowercase, so that the algorithm does not treat the same words in different cases as different
- Tokenization: Tokenization is just the term used to describe the process of converting the normal text strings into a list of tokens i.e words that we actually want. Sentence tokenizer can be used to find the list of sentences and Word tokenizer can be used to find the list of words in strings.

# The NLTK data package includes a pre-trained Punkt tokenizer for English.
- Removing Noise i.e everything that isn’t in a standard number or letter.
- Removing the Stop words. Sometimes, some extremely common words which would appear to be of little value in helping select documents matching a user need are excluded from the vocabulary entirely. These words are called stop words
- Stemming: Stemming is the process of reducing inflected (or sometimes derived) words to their stem, base or root form — generally a written word form. Example if we were to stem the following words: “Stems”, “Stemming”, “Stemmed”, “and Stemtization”, the result would be a single word “stem”.
- Lemmatization: A slight variant of stemming is lemmatization. The major difference between these is, that, stemming can often create non-existent words, whereas lemmas are actual words. So, your root stem, meaning the word you end up with, is not something you can just look up in a dictionary, but you can look up a lemma. Examples of Lemmatization are that “run” is a base form for words like “running” or “ran” or that the word “better” and “good” are in the same lemma so they are considered the same.

# Generating Response
After initial pre-processing, transforming text to a meaningful vector/array of numbers.

Texts that describes the occurrence of words within a document, involves two things:-
- A vocabulary of known words.
- A measure of the presence of known words.
