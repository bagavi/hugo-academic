---
title: "Medoids in almost linear time via multi-armed bandits"
authors:
- "**Vivek Bagaria**"
- Govinda Kamath
- Vasilis ntranos
- Martin Zhang
- David Tse
date: "2017-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: [1]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *AISTATS*

abstract: Computing the medoid of a large number of points in high-dimensional space is an increasingly common operation in many data science problems. We present an algorithm Med-dit which uses O(n log n) distance evaluations to compute the medoid with high probability. Med-dit is based on a connection with the multi-armed bandit problem. We evaluate the performance of Med-dit empirically on the Netflix-prize and the single-cell RNA-Seq datasets, containing hundreds of thousands of points living in tens of thousands of dimensions, and observe a "5-10"x improvement in performance over the current state of the art.

# Summary. An optional shortened abstract.
summary: Compute the medoid (high dimensional median) for n points in O(n log n) time.

tags:
- Machine Learning
- High dimensions
- Algorithm
- Bandits
featured: false

links:
url_pdf: https://arxiv.org/pdf/1711.00817
url_code: 'https://github.com/bagavi/Meddit'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/)

