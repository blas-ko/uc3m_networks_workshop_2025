# Link Prediction and Network Inference
**Blas Kolic 2025**

In this tutorial, we will learn how to train a machine learning model to predict missing/future links in a network. 

Real networks are noisy (we may not observe some interactions that did happen) and dynamic (new interactions happen over time). The idea here is that, given the usual characteristics of many empirical networks (e.g., high tradic closure, homophily, small-worldness), we can extract relevant characteristics as features and train a good-enough model that highly scores very probable missing or future interactions. 

First, we will compute some these characteristics by hand in a small network to gain some intuition. Then, we will move into a larger real network and build a machine learning pipeline using the concepts we saw in class.

**Outline of the tutorial**
1. **Analyze a small network**: Compute similarity features and visualize them.
2. **Link prediction model in bigger network**: Scale it up and build a machine learning pipeline for link prediction.
   1. Read, preprocess, and create a `networkx` network
   2. Create a training sample based on existing and non-existing links
   3. Compute a similarity score table for the sampled links
   4. Train a machine learning model with the features and sampled links
   5. Evaluate model performance
3. **Optional exercises**