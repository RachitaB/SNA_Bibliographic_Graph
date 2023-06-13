# SNA_Bibliographic_Graph

## Introduction
This analysis focuses on visualizing a bibliographic graph that represents the relationships between papers, authors, and citations in a heterogeneous network. By considering different types of nodes and edges, we constructed a comprehensive network and used visualization tools to display it. This visualization provides insights into the connections and structure of the academic domain, helping identify thematic clusters and patterns in the field of study.

## Dataset
The dataset used for this analysis is "IEEE_Finale_Data.csv" obtained from Kaggle.

## Methodology
#### Plotting Bibliographic Graph
  1. Data Collection: Gather bibliographic data, including authors, papers, citations, and metadata.
  2.  Data Preprocessing: Clean and organize the bibliographic data, resolving inconsistencies and creating a structured dataset.
  3.  Network Construction: Convert the bibliographic data into a network representation with multiple node types (authors, papers) and edge types (co-authorship, citation).
  4.  Subgraph Selection: Choose a specific subgraph to visualize, such as an author's network, a subset of papers, or a topic-related subgraph.
  5.  Network Visualization: Utilize visualization tools like NetworkX, Gephi, or Cytoscape to visually represent the selected subgraph.
  6.  Node and Edge Customization: Customize the visualization by assigning colors, sizes, labels, and other visual attributes to highlight important information or relationships.
  7.  Analysis and Insights: Analyze the visualized subgraph to gain insights about bibliographic relationships, identify clusters, influential authors/papers, and explore collaboration or citation patterns.

#### Node and Edge Classification using Clustering
Using clustering techniques, nodes and edges can be classified based on the number of topics or papers, thereby identifying similarity within the bibliographic graph. K-means Clustering: A popular unsupervised clustering algorithm that groups nodes or edges based on their similarity. The number of topics or papers can be used as features for applying K-means to cluster nodes or edges into distinct groups.
