Link Prediction in Dynamic Graphs
=================================

Link prediction in static and partially dynamic graphs i.e., graphs in which only the set of edges changes has been explored to a large extent by a large body of previous work. However, link prediction in fully dynamic graphs i.e., the ones in which both the sets of nodes and edges are ever changing, requires a simple yet efficient and effective algorithm for scaling up to large graphs. In this work, we propose an algorithm which utilises the local structure of a simple graph via depth first search to update it’s node embeddings as and when new nodes and edges are added and the existing ones are removed. We evaluated our algorithm on different graphs (sparse, dense, large and small) and observed that more than 90% links were correctly predicted with the best result at 99.5%.

Following are the contributions of this work,

- Efficient, simple and effective algorithms for learning node embeddings for a given simple graph for the task of link prediction have been proposed. In addition, for measuring the probability of existence of a link, we have proposed a measure based on the well known sigmoid function.

- The above algorithms have also been shown to work for updating the node embeddings when the structure of the given simple graph changes.

- Complexity analysis has been presented for the proposed algorithms for better theoretical upper bounds and suggestions have been made to ensure scalability on large graphs.

How To Use Code?
================

Following steps may be followed for re-using our code,

1. Upload the folder `linkpred` in your Google drive.
2. Upload the `LinkPrediction.ipynb` notebook on Google colab. Mount your Google drive so that notebook can interact with the above uploaded folder.
3. Run the first and the second cells and afterwards you can play with the rest of the notebook.

Make sure that the Google accounts in step 1 and step 2 are the same.
