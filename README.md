# CS224W : Machine Learning with Graphs (Stanford / Fall 2024)

[Course Link](https://web.stanford.edu/class/cs224w/)

Solutions to the assignments of the course __CS224W: Machine Learning with Graphs__ offered by Stanford University. The Fall 2024 offering of this class was chosen, as the assignments had more content.

The assignments consist of 5 Colab Notebooks and 3 Homeworks, each aiming to teach a different topic. Specifically:

- [Colab 1](CS224W_colab_1_kyuhyeok.ipynb): This Colab builds a simple node embedding pipeline using PyTorch. We start by exploring the [Karate Club](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.KarateClub) graph, convert it into tensors, and implement a basic embedding model from scratch to learn node representations.

- [Colab 2](CS224W_colab_2_kyuhyeok.ipynb): This notebook focuses on building a graph neural network using [PyTorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/) and applying it to two OGB ([Open Graph Benchmark](https://ogb.stanford.edu/)) [arxiv](https://ogb.stanford.edu/docs/nodeprop/#ogbn-arxiv) datasets. The goal is to benchmark the model on two tasks: node property prediction and graph property prediction. You'll start by learning how PyG represents graphs as tensors, then explore OGB datasets using the ogb package. Finally, you'll build, train, and evaluate your own GNN model on both prediction tasks.

- [Colab 3](CS224W_colab_3_kyuhyeok.ipynb): In this Colab, we implement the [GraphSAGE](https://arxiv.org/abs/1706.02216) layer from scratch and apply it to the [Cora](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.Planetoid) citation network, a standard benchmark for graph learning.

- [Colab 4](CS224W_colab_4_kyuhyeok.ipynb): In this Colab, we implement the [GAT](https://arxiv.org/abs/1710.10903) (Graph Attention Network) layer from scratch and apply it to the [Cora](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.Planetoid) citation network benchmark.

- [Colab 5](CS224W_colab_5_kyuhyeok.ipynb): This Colab notebook introduces heterogeneous graphs, which include different types of nodes and edges, unlike the homogeneous graphs we've seen before. You'll learn how to convert [NetworkX](https://networkx.org/) graphs into [DeepSNAP](https://github.com/snap-stanford/deepsnap) format and see how DeepSNAP represents these graphs using PyTorch Tensors. Then, you'll build heterogeneous graph neural networks using PyTorch Geometric and DeepSNAP, and apply them to a node property prediction task on the ACM dataset.

- [Homework 1](CS224W_hw1_KyuhyeokSeo.pdf): This homework explores the expressiveness of GNNs, the theory behind node embeddings, and the fundamentals of GCNs. It looks at how depth affects GNN performance, the role of random walks, and challenges like over-smoothing. It also connects node embeddings to matrix factorization and eigen decomposition, and introduces methods like node2vec and struct2vec. Finally, it examines GCN design choices, including aggregation functions and their relation to the Weisfeiler-Lehman test.

- [Homework 2](CS224W_hw2_KyuhyeokSeo.pdf): This homework focuses on knowledge graph embeddings and query reasoning. It begins with TransE, covering its loss function, the role of the margin parameter (gamma), normalization, and its expressiveness. Next, it compares the modeling power of TransE and RotatE, highlighting their strengths and limitations. Finally, it explores how to answer complex queries on knowledge graphs, including path and conjunctive queries, even when the graph is incomplete, introducing Query2box as a method for handling such cases.

- [Homework 3](CS224W_hw3_KyuhyeokSeo.pdf): This homework explores advanced topics in graph neural networks and relational learning. It starts by interpreting GNNs as MLPs over eigenvectors, covering concepts like batch node updates, single-layer MLPs, and extensions to methods like GraphSAGE. It then introduces LightGCN, emphasizing the benefits of using averaged embeddings, removing self-connections, and its connection to APPNP. Lastly, it dives into relational deep learning, focusing on schema graphs, relational entity graphs, computation graphs, and how message passing operates in relational settings.


## Resources

The resources that were used for the completion of the assignments are:

1. Online lectures of the course, available on [youtube](https://www.youtube.com/playlist?list=PLoROMvodv4rPLKxIpqhjhPgdQy7imNkDn).
2. The corresponding slides, available in the [course website](https://web.stanford.edu/class/cs224w/).
