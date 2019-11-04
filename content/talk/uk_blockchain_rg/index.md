---
title: "Boomerang: Redundancy Improves Latency and Throughput in Payment Networks"
event: 4th UK Blockchain Research Meetup

location: UK Blockchain Research Meetup, London
address:
  city: London
  country: United Kingdom


summary: Deconstructing the blockchain into its basic functionalities and systematically scaling up these to acheive optimal security, throughput and near optimal latency.


abstract: In multi-path routing schemes for payment-channel networks, Alice transfers funds to Bob by splitting them into partial payments and routing them along multiple paths. Undisclosed channel balances and mismatched transaction fees cause delays and failures on some payment paths. For atomic transfer schemes, these straggling paths stall the whole transfer. We show that the latency of transfers reduces when redundant payment paths are added. This frees up liquidity in payment channels and hence increases the throughput of the network. We devise Boomerang, a generic technique to be used on top of multi-path routing schemes to construct redundant payment paths free of counterparty risk. In our experiments, applying Boomerang to a baseline routing scheme leads to 40% latency reduction and 2x throughput increase. We build on ideas from publicly verifiable secret sharing, such that Alice learns a secret of Bob iff Bob overdraws funds from the redundant paths. Funds are forwarded using Boomerang contracts, which allow Alice to revert the transfer iff she has learned Bob's secret. We implement the Boomerang contract in Bitcoin Script.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2019-11-14T18:00:00Z"
date_end: "2019-11-14T19:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- internal-project

# Enable math on this page?
math: true
---

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
