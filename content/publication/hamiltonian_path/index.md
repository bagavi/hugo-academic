---
title: "Hidden Hamiltonian Cycle Recovery via Linear Programming"
authors:
- "**Vivek Bagaria**"
- Jian Ding
- David Tse
- Yihoong Wu
- Jiaming Xu
date: "2018-04-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Operations Research*
publication_short: In *Operations Research*

abstract: We introduce the problem of hidden Hamiltonian cycle recovery, where there is an unknown Hamiltonian cycle in an n-vertex complete graph that needs to be inferred from noisy edge measurements. The measurements are independent and distributed according to $\calP_n$ for edges in the cycle and $\calQ_n$ otherwise. This formulation is motivated by a problem in genome assembly, where the goal is to order a set of contigs (genome subsequences) according to their positions on the genome using long-range linking measurements between the contigs. Computing the maximum likelihood estimate in this model reduces to a Traveling Salesman Problem (TSP). Despite the NP-hardness of TSP, we show that a simple linear programming (LP) relaxation, namely the fractional 2-factor (F2F) LP, recovers the hidden Hamiltonian cycle with high probability as n→∞ provided that αn−logn→∞, where is the Rényi divergence of order 12. This condition is information-theoretically optimal in the sense that, under mild distributional assumptions, αn≥(1+o(1))logn is necessary for any algorithm to succeed regardless of the computational cost. Departing from the usual proof techniques based on dual witness construction, the analysis relies on the combinatorial characterization (in particular, the half-integrality) of the extreme points of the F2F polytope. Represented as bicolored multi-graphs, these extreme points are further decomposed into simpler "blossom-type" structures for the large deviation analysis and counting arguments. Evaluation of the algorithm on real data shows improvements over existing approaches.

# Summary. An optional shortened abstract.
summary: Average case instance of the traveling salesman problem for a graph with V vertices and E edges can be solved in O(VE) time via LP.

tags:
- Machine Learning
- Algorithm
- Analysis
- Python
featured: true

links:
url_pdf: https://arxiv.org/pdf/1804.05436
url_code: 'https://github.com/bagavi/HiC_LP'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

---


