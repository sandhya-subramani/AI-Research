# AI-Research-Publications

## A Novel Approach of Neural Topic Modelling for Document Clustering

Topic modelling is a text mining technique to discover common topics in a collection of documents.
The proposed methodology of topic modelling used artificial neural networks to improve the clustering mechanism of similar documents by modelling probabilistic relations between the topics, documents and vocabulary. 

Currently, while topic modelling and clustering are considered to be manifestations of unsupervised learning, and neural networks on the other hand are used for supervised learning problems, Neural Topic Modelling reformulated topic modelling into a supervised learning task by defining an objective function whose loss function had to be minimized.
Custom input embedding layers were designed in order to extract the semantic relationships between the words in the corpus, and the output of the modelpresented a topic probability distribution for each document.
The documents with similar distributions were then bucketed together based on the criteria of meeting the threshold value of a simple distance based similarity metric, such as cosine similarity.

The model was implemented using Keras with TensorFlow backend and the effectiveness of the clustering was validated on the IMDB Movie dataset and the News Aggregator dataset from
UCI. On comparison with other commonly used clustering mechanisms in combination with traditional topic models, the proposed model delivered an improved Silhouette Co-efficient
Score and Davies-Bouldin Index, along with an increased data handling capacity, thereby making the solution scalable. 

## Multiheaded Structured Self-Attention Using Neural Averaging Layer

The proposed Attention based Artificial Neural Network model aimed to provide higher prediction accuracy as well as faster training period for classification tasks by designing
a Learnt Sentence Embedding that captured the different themes present in a sentence into a single embedding. 

This was performed by means of a Neural Averaging Layer that employed a weighted architecture to combine the various themes from the multiple heads of the attention layer output. The model also incorporated positional encoding to the word representations of the input in order to accommodate for flexible length in sentences during prediction. The model was implemented in PyTorch on a 16 GB RAM processor, and the efficacy was tested on the IMDB Movie Reviews Sentiment Dataset and the Reuters Newswire Topics Classification Dataset. The attention weights obtained from the model also helped visualize and interpret the model performance, as a heat map plotting of the attention distribution across the text corpus. 

Upon comparison with the base model and other Deep Learning model architectures, the proposed model was found to result the best accuracy as well as the quickest training time, while being computationally more expensive
