Title: Graph Anomaly Detection With Graph Neural Networks: Current Status and Challenges

Authors: Hwan Kim, Byung Suk Lee, Won-yong Shin and Sungsu Lim 

Venue: IEEE Xplore

Problem and motivation

The article explains how graphs are used to model real-world systems as they focus on relationships between data objects. It explains how traditional anomaly detection struggles with graph-structured data due to its complexity in identifying anomalies like unusual nodes or edges. By using Graph Neural Networks (GNNs), it can learn from both node attributes and graph structures. It needs to detect both static and dynamic graph anomalies, especially when transitioning from simulations to real-world environments.

Methods and results

	The paper goes into detail about anomaly types like node, edge, and subgraph anomalies and discusses GNN architecture. For static graphs, to detect node anomalies, there are frameworks like GCN-based GAE that use encoders and decoders to learn normal behavior and detect outliers through reconstruction errors. For edge anomalies, it uses models like AANE to calculate loss-based anomaly scores on relationships. In dynamic graphs, there are GCN hybrids that track evolving structural patterns and detect anomalies over time.

Relevance to your own research

	The paper is relevant to my research as it focuses on detecting anomalies in robotic navigation using GNNs. Using the techniques discussed, like GCN-based GAE for node scoring and dynamic detection, it applies to GPS spoofing. It also highlights the challenges in trust modeling and real-time response, like data imbalance.

