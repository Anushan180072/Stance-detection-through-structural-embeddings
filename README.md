# Stance-detection-through-structural-embeddings
Node2Vec-based graph embeddings and node representation learning<br><br>

This project implements Node2Vec to generate low-dimensional vector representations (embeddings) for nodes in a graph. The learned embeddings capture structural relationships between nodes and can be used for downstream machine learning tasks such as node classification, clustering, and similarity analysis.<br><br><br>

**📌 Project Overview**

Graphs are widely used to represent relationships in real-world systems such as social networks, citation networks, and recommendation systems.

This project applies Node2Vec, a graph embedding algorithm that:

Performs biased random walks on the graph

Treats walks as sentences

Uses Word2Vec to learn node embeddings

Preserves structural and neighborhood information<br><br><br>

**🛠 Technologies Used**

Python

NetworkX

Node2Vec

Gensim (Word2Vec)

NumPy

Scikit-learn

Matplotlib<br><br><br>

**⚙️ Methodology**

Construct or load a graph using NetworkX

Generate random walks from each node

Train a Word2Vec model on the generated walks

Learn low-dimensional vector embeddings for each node

Apply embeddings to tasks like similarity search or node classification
