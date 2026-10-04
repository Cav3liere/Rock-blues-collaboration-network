# 🎸 Rock & Blues Artist Collaboration Network

This project models the collaboration network of classic rock and blues artists as an undirected graph, exploring community structures and predicting future musical collaborations.

## 🛠️ Tech Stack & Libraries
- **Data Collection:** MusicBrainz API (`musicbrainzngs`)
- **Network Analysis:** NetworkX (graph construction, metrics, clustering, shortest paths)
- **Community Detection:** Louvain algorithm (`python-louvain`)
- **Graph Embeddings & Machine Learning:** Node2Vec, Scikit-Learn (Random Forest, Logistic Regression)

## 📊 Key Highlights
- **Network Stats:** Built a graph of 549 nodes and 585 edges, capturing core artists and second-level collaborators.
- **Centrality Analysis:** Identified key network bridges (e.g., Eric Clapton and Mark Knopfler) using betweenness and closeness centrality.
- **Community Detection:** Achieved an exceptional modularity score of ~0.87 using the Louvain algorithm, mapping real-world musical sub-genres.
- **Link Prediction:** Trained a Random Forest classifier on Node2Vec structural embeddings to predict new artist collaborations with an F1-score of ~0.94
