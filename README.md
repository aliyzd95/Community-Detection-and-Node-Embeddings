# Community-Detection-and-Node-Embeddings

This project focuses on **community detection** in graphs using different methods and **node embeddings**. The objective is to explore the effectiveness of various community detection algorithms and how well they perform when applied to graphs with node embeddings. The project involves the following key tasks:

1. **Community Detection Algorithms**:
   - Several algorithms are used to detect communities in graphs, such as **Label Propagation**, **Louvain**, **Girvan-Newman**, **Kernighan-Lin**, and **Infomap**.
   - Each algorithm helps partition the graph into meaningful clusters or communities of nodes, with the goal of understanding the structure of the graph.

2. **Node Embedding Methods**:
   - Node embeddings are generated using methods like **HOPE**, **DeepWalk**, and **Node2Vec**. These methods represent nodes in a lower-dimensional vector space, capturing the structural relationships between nodes.
   - The embeddings are then used as input for community detection algorithms to improve or compare the quality of the detected communities.

3. **Dimensionality Reduction**:
   - **PCA (Principal Component Analysis)** is applied to reduce the dimensionality of node features, simplifying the graph's structure while retaining critical information for community detection.

4. **Evaluation Metrics**:
   - The quality of community detection results is evaluated using multiple metrics:
     - **ARI (Adjusted Rand Index)**: Measures the similarity between the detected communities and ground-truth communities, adjusted for chance.
     - **NMI (Normalized Mutual Information)**: Measures the mutual information between the detected communities and ground-truth communities.
     - **Modularity**: A measure of the strength of division of a graph into communities, indicating the quality of community structure.

This project integrates graph theory, machine learning, and community detection algorithms to understand complex network structures and improve the detection of underlying communities. The analysis provides insights into the performance of different methods and their applicability to real-world graph data.
