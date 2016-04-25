# Candidate2Vec
This repository aims to represent the current political candidates in a vectorized space in order to determine some distances between them. The primary means of vectorizing the candidates will be creating a representation of each candidate as the topics about which they discuss. To do this I’ll be using <a href='https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation'>Latent Dirichlet allocation </a> (LDA). Once we have a representation of the different candidates, it will represent a percentage of topics each candidate’s speech is about. We’ll then use lda2vec (all credit goes to Chris Moody find the package <a href='https://github.com/cemoody/lda2vec'>here</a>,  and a copy of the presentation <a href='http://www.slideshare.net/ChristopherMoody3/word2vec-lda-and-introducing-a-new-hybrid-algorithm-lda2vec-57135994'>here</a>.  
Once we have the vectorized candidates we can look at distances between one another and infer some meanings about the topics, as well as the candidates themselves.

Current status:
Transcripts have been acquired, still processing them now.


