---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "PairConnect: A Compute-Efficient MLP Alternative to Attention"
authors: [Zhaozhuo Xu, Minghao Yan, Junyan Zhang, Anshumali Shrivastava]
date: 2021-06-17T10:40:23-06:00
doi: ""

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-12T10:40:23-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In submission to NeurIPS 2021.
publication_short: Arxiv
abstract: "Transformer models have demonstrated superior performance in natural language processing. The dot product self-attention in Transformer allows us to model interactions between words. However, this modeling comes with significant computational overhead. In this work, we revisit the memory-compute trade-off associated with Transformer, particularly multi-head attention, and show a memory-heavy but significantly more compute-efficient alternative to Transformer. Our proposal, denoted as PairConnect, a multilayer perceptron (MLP), models the pairwise interaction between words by explicit pairwise word embeddings. As a result, PairConnect substitutes self dot product with a simple embedding lookup. We show mathematically that despite being an MLP, our compute-efficient PairConnect is strictly more expressive than Transformer. Our experiment on language modeling tasks suggests that PairConnect could achieve comparable results with Transformer while reducing the computational cost associated with inference significantly."
# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2106.08235v1.pdf
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
