# Text-summariser-Task

Libraries used
 - Pandas
 - Torch
 - Summarizer
 - Time
 
**Bert Extractive Summarizer** is used, which is a library that gives us access to a pre-trained BERT-based text summarization model, as well as some really intuitive functions for using it.

DistilBERT English language model pretrained on the same data used to pretrain Bert (concatenation of the Toronto Book Corpus and full English Wikipedia) using distillation with the supervision of the bert-base-uncased version of Bert.
The model has **6 layers**, **768 dimension** and **12 heads**, totalizing **66M parameters**.
