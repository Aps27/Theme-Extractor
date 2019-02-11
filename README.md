# Theme-Extractor
A program to create a theme extractor using python libraries to extract top 3 themes from the story : [http://www.textfiles.com/stories/3wishes.txt]
I have used the concept of Latent Dirichlet Allocation (LDA) in Python.
LDA is used to classify text in a document to a particular topic. It builds a topic per document model and words per topic model, modeled as Dirichlet distributions.

Each document is modeled as a multinomial distribution of topics and each topic is modeled as a multinomial distribution of words.
LDA assumes that the every chunk of text we feed into it will contain words that are somehow related. Therefore choosing the right corpus of data is crucial.
It also assumes documents are produced from a mixture of topics. Those topics then generate words based on their probability distribution.
To learn more about LDA please check out this link [http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf]
