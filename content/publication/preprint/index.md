---
abstract: "Subgraph isomorphism counting is an important problem on graphs, as
  many graph-based tasks exploit recurring sub-graph patterns. Classical methods
  usually boil down to a backtracking framework that needs to navigate a huge
  search space with prohibitive computational costs. Some recent studies resort
  to graph neural networks (GNNs) to learn a low-dimensional representation for
  both the query and input graphs, in order to predict the number of subgraph
  isomorphisms on the input graph. However, typical GNNs employ a node-centric
  message passing scheme that receives and aggregates messages on nodes, which
  is inadequate in complex structure matching for isomorphism counting.
  Moreover, on

  an input graph, the space of possible query graphs is enormous, and
  different parts of the input graph will be triggered to match different
  queries. Thus, expecting a fixed representation of the input graph to match
  diversely structured query graphs is unrealistic. In this paper, we propose a
  novel GNN called Count-GNN for subgraph isomorphism count\x02ing, to deal with
  the above challenges. At the edge level, given that an edge is an atomic unit
  of encoding graph structures, we propose an edge-centric message passing
  scheme, where messages on edges are propagated and aggregated based on the
  edge adjacency to preserve fine-grained structural information. At the graph
  level, we modulate the input graph rep\x02resentation conditioned on the
  query, so that the input graph can be adapted to each query individually to
  improve their matching. Finally, we conduct extensive experiments on a number
  of benchmark datasets to demonstrate the superior performance of Count-GNN."
slides: example
url_pdf: http://arxiv.org/pdf/1512.04133v1
publication_types:
  - "1"
authors:
  - admin
  - Zemin Liu
  - Yuan Fang
  - Xinming Zhang
author_notes:
  - Equal contribution
  - Equal contribution
publication: ""
summary: ""
url_dataset: "#"
url_project: ""
publication_short: In *AAAI-23*
url_source: "#"
url_video: "#"
title: Learning to Count Isomorphisms with Graph Neural Networks
featured: false
tags: []
date: 2023-02-19T14:00:57.250Z
url_slides: ""
links:
  - name: Custom Link
    url: http://example.org
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)"
  focal_point: ""
  preview_only: false
  filename: featured.jpg.png
publishDate: 2017-01-01T00:00:00.000Z
url_poster: "#"
url_code: https://github.com/wowchemy/wowchemy-hugo-themes
doi: ""
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
