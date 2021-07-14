## CS-274C Final Project - Tag Prediction on Stack Exchange Posts
## Introduction
A very important application of text and data mining (TDM) is the identification of
keywords or tags from input text. This is especially useful in the case of Question
and Answer (QA) websites such as StackExchange or Quora. StackExchange is
one of the most popular QA websites, where each community addresses questions
pertaining to a particular domain such as math, programming, gaming and so on.
Tagging allows users to explore related content, build and showcase expertise in a
given area, facilitates the search for questions and in general, increases the visibility
of the post. We present a model that uses transfer learning to automatically assign
tags to questions from the QA site StackExchange based on the title and body of
the question. We experimented with two techniques Word2Vec and BERT based
approach. In particular we try to evaluate the performance of these NLP Language
models for our multi-label classification task. When evaluated on an unseen test
set, our LSTM model with Word2vec embeddings achieved a loss of 2.61 and an
accuracy of 34.49% on this task while the BERT based model achieved a loss of
0.10.
