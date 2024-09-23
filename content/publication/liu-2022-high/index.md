---
title: "High-order Line Graphs of Non-uniform Hypergraphs: Algorithms, Applications, and Experimental Analysis"
date: 2022-01-01
publishDate: 2022-07-02T15:38:54.184827Z
authors: ["Xu T Liu", "Jesun Firoz", "Sinan Aksoy", "Ilya Amburg", "Andrew Lumsdaine", "Cliff Joslyn", "Assefaw H Gebremedhin", "Brenda Praggastis"]
publication_types: ["2"]
abstract: "Hypergraphs offer flexible and robust data rep- resentations for many applications, but methods that work directly on hypergraphs are not readily available and tend to be prohibitively expensive. Much of the current analysis of hypergraphs relies on first performing a graph expansion – either based on the nodes (clique expansion), or on the hyperedges (line graph) – and then running standard graph analytics on the resulting representative graph. However, this approach suffers from massive space complexity and high computational cost with increasing hypergraph size. Here, we present efficient, parallel algorithms to accelerate and reduce the memory footprint of higher-order graph expansions of hypergraphs. Our results focus on the hyperedge-based s-line graph expansion, but the methods we develop work for higher-order clique expansions as well. To the best of our knowledge, ours is the first framework to enable hypergraph spectral analysis of a large dataset on a single shared- memory machine. Our methods enable the analysis of datasets from many domains that previous graph-expansion-based models are unable to provide. The proposed s-line graph computation algorithms are orders of magnitude faster than state-of-the-art sparse general matrix-matrix multiplication methods, and obtain approximately 2 − 31 X speedup over a prior state-of-the-art heuristic-based algorithm for s-line graph computation."
featured: false
publication: "2022 IEEE International Parallel and Distributed Processing Symposium (IPDPS)"
tags: ["hypergraphs", "HPC"]
doi: "10.1109/IPDPS53621.2022.00081"
---
