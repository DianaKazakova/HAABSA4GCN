# HAABSA4GCN

Code for A Hybrid Approach for Aspect-Based Sentiment Analysis using 4 Graph Convolutional Networks. All software is written in Jupyter Notebook and uses the TensorFlow framework (https://www.tensorflow.org/) and torch library.

### Introduction

This project introduces HAABSA4GCN, an enhanced model building on the state-of-the-art HAABSA++. HAABSA4GCN integrates the ontology from HAABSA++ with an innovative backup model utilizing the Graph Convolutional Neural (GCN) network, referred to as 4GCN. This backup model leverages four types of graphs: syntactic, semantic, lexical, and ontological. The SemEval 2015 and SemEval 2016 datasets are employed for evaluation. Results indicate that HAABSA4GCN surpasses HAABSA++ in performance, demonstrating that incorporating multiple graphs enhances prediction accuracy. Notably, 4GCN alone outperforms HAABSA4GCN, suggesting that graph-based models could be more effectively combined with an ontology, especially when dealing with cases where the ontology is inconclusive.

### Features

- Combines domain-specific ontology from HAABSA++ with a novel GCN-based backup model.
- Utilizes four types of graphs: syntactic, semantic, lexical, and ontological.
- Evaluated on SemEval 2015 and SemEval 2016 datasets, demonstrating improved performance over HAABSA++.

## Installation and Setup Instructions (Windows):

- Download ontology: [Heracles Ontology](https://github.com/KSchouten/Heracles/tree/master/src/main/resources/externalData).
- Necessary sentiment datasets are stored in the data folder.
- Necessary libraries are already included in the code files.
- The Python version used for the model - 3.6

