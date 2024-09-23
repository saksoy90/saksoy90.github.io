---
title: "Parallel Algorithms for Efficient Computation of High-Order Line Graphs of Hypergraphs"
date: 2021-12-01
publishDate: 2022-07-02T15:38:54.187430Z
authors: ["Xu T. Liu", "Jesun Firoz", "Andrew Lumsdaine", "Cliff Joslyn", "Sinan Aksoy", "Brenda Praggastis", "Assefaw H. Gebremedhin"]
publication_types: ["2"]
abstract: "This paper considers structures of systems beyond dyadic (pairwise) interactions and investigates mathematical modeling of multi-way interactions and connections as hypergraphs, where captured relationships among system entities are set-valued. To date, in most situations, entities in a hypergraph are considered connected if there is at least one common neighbor. However, minimal commonality sometimes discards the strength of connections and interactions among groups. To this end, considering the width of a connection, referred to as the s-overlap of neighbors, provides more meaningful insights into how closely the communities or entities interact with each other. In addition, s-overlap computation is the fundamental kernel to construct the line graph of a hypergraph, a low-order approximation of the hypergraph which can carry significant information about the original hypergraph. Subsequent stages of a data analytics pipeline then can apply highly tuned graph algorithms on the line graph to reveal important features. Given a hypergraph, computing the s-overlaps by exhaustively considering all pairwise entities can be computationally prohibitive. To tackle this challenge, we develop efficient algorithms to compute s-overlaps and the corresponding line graph of a hypergraph. We propose several heuristics to avoid execution of redundant work and improve performance of the s-overlap computation. Our parallel algorithm, combined with these heuristics, is orders of magnitude (more than 10x) faster than the naive algorithm in all cases and the SpGEMM algorithm with filtration in most cases (especially with large s value)."
featured: false
publication: "*2021 IEEE 28th International Conference on High Performance Computing, Data, and Analytics (HiPC)*"
url_pdf: "http://dx.doi.org/10.1109/HiPC53243.2021.00045"
doi: "10.1109/hipc53243.2021.00045"
tags: ['hypergraphs','HPC']
---
