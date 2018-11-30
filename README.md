# NLP-Text-classification-
Our objective here is to fine-tune a pre-trained model and use it for text classification on a new dataset
. We will implement ULMFiT in this process.
The interesting thing here is that this new data is quite small in size (&lt;1000 labeled instances). 
A neural network model trained from scratch would overfit on such a small dataset. 
Hence, I would like to see whether ULMFiT does a great job at this task as promised in the paper.  D
ataset: We will use the 20 Newsgroup dataset available in sklearn.datasets. As the name suggests,
it includes text documents from 20 different newsgroups.
