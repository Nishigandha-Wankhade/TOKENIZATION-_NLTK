This file shows the basic functionality of functions from NLTK package used for tokenization.
sent_tokenize(corpus)       : used to convert paragraphs to sentences based on full stop and exclamation punctuation symbols.
word_tokenize(corpus)       : helps to get single words from sentences.
wordpunct_tokenize(corpus)  : help identify single words, even punctuation symbols will consider as a single word.
TreebankWordTokenizer()     : In most cases it will consider only a last full stop as a single word and not all other full stops (which are present in between paragraphs).
