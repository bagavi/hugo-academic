---
title: "Boomerang: Redundancy Improves Latency and Throughput in Payment Networks"
authors:

- "**Vivek Bagaria**"
- Joachim Neu
- David Tse
date: "2019-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [3]

# Publication name and optional abbreviated publication name.
publication_short: Preprint

abstract: In multi-path routing schemes for payment-channel networks, Alice transfers funds to Bob by splitting them into partial payments and routing them along multiple paths. Undisclosed channel balances and mismatched transaction fees cause delays and failures on some payment paths. For atomic transfer schemes, these straggling paths stall the whole transfer. We show that the latency of transfers reduces when redundant payment paths are added. This frees up liquidity in payment channels and hence increases the throughput of the network. We devise Boomerang, a generic technique to be used on top of multi-path routing schemes to construct redundant payment paths free of counterparty risk. In our experiments, applying Boomerang to a baseline routing scheme leads to 40% latency reduction and 2x throughput increase. We build on ideas from publicly verifiable secret sharing, such that Alice learns a secret of Bob iff Bob overdraws funds from the redundant paths. Funds are forwarded using Boomerang contracts, which allow Alice to revert the transfer iff she has learned Bob's secret. We implement the Boomerang contract in Bitcoin Script.

# Summary. An optional shortened abstract.
summary: Undisclosed channel balances and mismatched transaction fees cause failures on payment paths. Boomerang is a framework to add risk-free redundant payment paths to improve the latency and throughput of the system by 2x.

tags:
- Blockchain
- Payment network
- High performance
- Algorithm
featured: true

links:
url_pdf: https://arxiv.org/pdf/1910.01834
url_code: 'https://github.com/tse-group/boomerang'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

---

