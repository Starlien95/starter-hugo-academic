---
title: Learning to Count Isomorphisms with Graph Neural Networks
publication_types:
  - "1"
authors:
  - admin
  - Zemin Liu
  - Yuan Fang
  - Xinming Zhang
publication_short: In *AAAI-23*
abstract: Subgraph isomorphism counting is an important problem on graphs, as
  many graph-based tasks exploit recurring subgraph patterns. Classical methods
  usually boil down to a backtracking framework that needs to navigate a huge
  search space with prohibitive computational costs. Some recent studies resort
  to graph neural networks (GNNs) to learn a low-dimensional representation for
  both the query and input graphs, in order to predict the number of subgraph
  isomorphisms on the input graph. However, typical GNNs employ a node-centric
  message passing scheme that receives and aggregates messages on nodes, which
  is inadequate in complex structure matching for isomorphism counting.
  Moreover, on an input graph, the space of possible query graphs is enormous,
  and different parts of the input graph will be triggered to match different
  queries. Thus, expecting a fixed representation of the input graph to match
  diversely structured query graphs is unrealistic. In this paper, we propose a
  novel GNN called Count-GNN for subgraph isomorphism counting, to deal with the
  above challenges. At the edge level, given that an edge is an atomic unit of
  encoding graph structures, we propose an edge-centric message passing scheme,
  where messages on edges are propagated and aggregated based on the edge
  adjacency to preserve fine-grained structural information. At the graph level,
  we modulate the input graph representation conditioned on the query, so that
  the input graph can be adapted to each query individually to improve their
  matching. Finally, we conduct extensive experiments on a number of benchmark
  datasets to demonstrate the superior performance of Count-GNN.
draft: false
featured: false
tags: []
slides: ""
url_pdf: https://arxiv.org/pdf/2302.03266.pdf
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: feature.jpg
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes:
  - Equal contribution
  - Equal contribution
doi: ""
publication: ""
projects: []
date: 2023-02-19T14:50:02.711Z
url_slides: ""
publishDate: ""
url_poster: ""
url_code: https://github.com/Starlien95/Count-GNN
---
