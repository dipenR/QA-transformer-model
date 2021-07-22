# QA-transformer-model

This project uses BERT to perform the downstream tasking question answering on boolean (yes/no) questions. 
It uses HuggingFace to install and train the model and its tokenizer and then uses Pytorch to customize the model for boolean question answering. This model acheives a 73% accuracy on the test set but can be improved with the use of a GPU strong enough to handle a larger batch size.
the .py version of the file exists for easier viewing and reading while the .ipynb version of the file exists for better pipelining and testing.

Dependencies: pytorch, transformers, datasets, pandas (to generate a prediction file).
