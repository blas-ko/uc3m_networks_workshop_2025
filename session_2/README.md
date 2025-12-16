# Network models and structural analysis
**Blas Kolic, 2025**

In this tutorial, we take a deeper dive into networks by exploring several of their structural properties. We begin with one of the most common and powerful tools in network analysis: centrality measures. Then, we learn how to draw informative network visualizations using `networkx`, breaking down the key elements involved: placing nodes, drawing edges, adding labels, and coloring nodes according to network features. Then, we will extract significant clusters using community detection methods and assess the quality of the detected communities. Finally, we generate random networks using different network models and use them as a null benchmark to test whether features of real networks can be explained by randomness.

We will work with the **2025 Conclave social network**, a dataset capturing relationships between cardinals. This network was constructed and analyzed by a group of scholars at Bocconi University. Their analysis—conducted after Pope Francis passed away but **before** the new Pope was elected—found that Cardinal Prevost was the most central figure in terms of status. In network terms, he had the highest *eigenvector centrality*: he was important because he was connected to other important nodes. You can find the original press article [here](https://www.unibocconi.it/en/news/network-conclave) and the GitHub repository with raw data [here](https://github.com/leonardorizzo/Conclave2025). A cleaned and processed version of the network is included at `session_2/data/conclave/edgelist_conclave_final.csv`, which we will analyze in this tutorial.

**Structure of the tutorial**
1. **Reading**: Load and process the Conclave social network  
2. **Centrality**: Measure which nodes are most important in the network  
3. **Network visualization**: Create a visualization highlighting key nodes and features  
4. **Community detection**: Identify communities the from network structure and compute modularity  
5. **Network models**: Generate random networks and compare them to the empirical network  
6. **Optional exercises**: Practice your coding and network analysis skills  