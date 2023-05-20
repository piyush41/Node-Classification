# Node-Classification

We consider the problem of classifying nodes (such as documents) in a graph (such as a citation
network), where labels are only available for a small subset of nodes. This problem can be framed
as graph-based semi-supervised learning
The model is used for a node prediction task on the [Cora dataset](https://relational.fit.cvut.cz/dataset/CORA) to predict the subject of a paper given its words and citations network.
Graph neural networks is the prefered neural network architecture for processing data structured as graphs (for example, social networks or molecule structures), yielding better results than fully-connected networks or convolutional networks.

Implemented 2 models here:
1. With scalable approach for semi-supervised learning on graph-structured
data that is based on an efficient variant of convolutional neural networks which
operate directly on graphs. [GCN](https://arxiv.org/pdf/1609.02907.pdf)

2. GAT(graph attention network) architectures
that operate on graph-structured data, leveraging masked self-attentional layers to
address the shortcomings of prior methods based on graph convolutions or their
approximations.
