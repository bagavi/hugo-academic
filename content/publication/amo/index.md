---
title: "Adaptive Monte-Carlo Optimization"
authors:
- "**Vivek Bagaria**"
- Govinda Kamath
- David Tse
date: "2018-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [3]

# Publication name and optional abbreviated publication name.
#publication: In *Source Themes Conference*
publication_short: Preprint

abstract: The celebrated Monte Carlo method estimates a quantity that is expensive to compute by random sampling. We propose adaptive Monte Carlo optimization - a general framework for discrete optimization of an expensive-to-compute function by adaptive random sampling. Applications of this framework have already appeared in machine learning but are tied to their specific contexts and developed in isolation. We take a unified view and show that the framework has broad applicability by applying it on several common machine learning problems - k nearest neighbors, hierarchical clustering and maximum mutual information feature selection. On real data we show that this framework allows us to develop algorithms that confer a gain of a magnitude or two over exact computation. We also characterize the performance gain theoretically under regularity assumptions on the data that we verify in real world data. 

# Summary. An optional shortened abstract.
summary: State of the art algorithms for k-nearest neighbhours, k-means, heirarchical clustering based on adaptive sampling via multi armed bandits. . Our implementation improves on the previous best algorithms by 10x in wall-clock time.

tags:
- Machine Learning
- High dimensions
- Algorithm
- Bandits
- C++

featured: true

links:
url_pdf: https://arxiv.org/pdf/1805.08321
url_code: 'https://github.com/govinda-kamath/combinatorial_MAB'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'	

---

