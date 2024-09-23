---
title: "A generative graph model for electrical infrastructure networks"
date: 2018-08-01
publishDate: 2019-08-25T20:38:53.050118Z
authors: ["Sinan G. Aksoy", "Emilie Purvine", "Eduardo Cotilla-Sanchez", "Mahantesh Halappanavar"]
publication_types: ["2"]
abstract: "We propose a generative graph model for electrical infrastructure networks that accounts for heterogeneity in both node and edge type. To inform the model design, we analyse the properties of power grid graphs derived from the U.S. Eastern Interconnection, Texas Interconnection and Poland transmission system power grids. Across these datasets, we find subgraphs induced by nodes of the same voltage level exhibit shared structural properties atypical to small-world networks including low local clustering, large diameter and large average distance. On the other hand, we find subgraphs induced by transformer edges linking nodes of different voltage types contain a more limited structure, consisting mainly of small, disjoint star graphs. The goal of our proposed model is to match both these inter and intra-network properties by proceeding in two phases: the first phase, adapts the Chung-Lu random graph model, taking desired vertex degrees and desired diameter as inputs, while the second phase of the model is based on a simpler random star graph generation process. We test the model’s performance by comparing its output across many runs to the aforementioned real data. In nearly all categories tested, we find our model is more accurate in reproducing the unusual mixture of properties apparent in the data than the Chung-Lu model. We also include graph visualization comparisons, a brief analysis of edge-deletion resiliency, and guidelines for artificially generating the model inputs in the absence of real data."
featured: false
publication: "*Journal of Complex Networks*"
doi: "10.1093/comnet/cny016"
tags: ["power grid", "graph generation"]
---
