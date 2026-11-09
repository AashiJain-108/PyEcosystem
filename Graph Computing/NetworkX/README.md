## NetworkX

NetworkX is a Python package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.

### Official Documentation
https://pypi.org/project/networkx/

### How to install it?
use Python's package manager, pip
- pip install networkx

### Conceptually
NetworkX translates mathematical graph theory into Pythonic data structures.

### Python Dictionary-of-Dictionaries Backend
Under the hood, NetworkX doesn't rely on a rigid C-matrix structure for its default implementation; instead, it uses a Python dictionary-of-dictionaries structure.

- The outer dictionary holds the nodes.

- The inner dictionary holds the neighbors of a given node.

- Associated values store edge attributes (like weight, timestamp, or label).

This design makes NetworkX extremely flexible, allowing you to attach arbitrary Python objects (strings, numbers, or even custom classes) as attributes to nodes and edges.

### What Does Netwrokx Package Provide?
NetworkX is a comprehensive toolkit for graph theory and network analysis. It provides:

**Graph Data Structures:** Flexible implementations for undirected graphs, directed graphs, multigraphs, and multi-di-graphs.

**Standard Graph Generators:** Built-in functions to create classic, random, and small-world graphs (e.g., Erdős–Rényi, Watts–Strogatz, Barabási–Albert scale-free networks).

**Algorithms Library:** Over 100 graph algorithms covering shortest paths, flow networks, cluster coefficients, matching, domination, and connectivity.

**Centrality & Ranking Measures:** Tools to measure node importance using PageRank, Betweenness, Closeness, Eigenvector, and Degree centrality.

**I/O Formats:** Built-in support for reading and writing networks in standard formats like EdgeList, AdjacencyList, GEXF, GraphML, GML, and JSON.


### My Technical Observation:

---

### Learning Resources
