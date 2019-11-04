---
title: "Prism: Deconstructing the Blockchain to Approach Physical Limits"
authors:
- "**Vivek Bagaria**"
- Sreeram Kannan
- David Tse
- Giulia Fanti
- Pramod Viswanath
date: "2018-10-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized, 1 = Conference paper, 2 = Journal article,
# 3 = Preprint / Working Paper, 4 = Report, 5 = Book, 6 = Book section,
# 7 = Thesis, 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *ACM Conference on Computer and Communications Security*
publication_short: In *ACM CCS*

abstract: Transaction throughput, confirmation latency and confirmation reliability are fundamental performance measures of any blockchain system in addition to its security. In a decentralized setting, these measures are limited by two underlying physical network attributes - communication capacity and speed-of-light propagation delay. Existing systems operate far away from these physical limits. In this work we introduce Prism, a new proof-of-work blockchain protocol, which can achieve '1') security against up to '50'% adversarial hashing power, '2') optimal throughput up to the capacity C of the network, '3') confirmation latency for honest transactions proportional to the propagation delay D, with confirmation error probability exponentially small in CD , '4') eventual total ordering of all transactions. Our approach to the design of this protocol is based on deconstructing the blockchain into its basic functionalities and systematically scaling up these functionalities to approach their physical limits.



# Summary. An optional shortened abstract.
summary: Deconstructing the blockchain into its basic functionalities and systematically scaling up these to acheive optimal security, throughput and near optimal latency.

tags:
- Blockchain
- Security
- Proof of Work
- Algorithm
- Optimal
featured: true

links:
url_pdf: https://arxiv.org/pdf/1810.08092.pdf
url_code: 'https://github.com/yangl1996/prism-rust'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'
---


