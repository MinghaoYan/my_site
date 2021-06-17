---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Fast Processing and Querying of 170TB of Genomics Data via a Repeated And Merged BloOm Filter (RAMBO)"
authors: [Gaurav Gupta*, Minghao Yan*, Benjamin Coleman, Bryce Kille, R. A. Leo Elworth, Tharun Medini, Todd Treangen, Anshumali Shrivastava]
date: 2021-03-12T10:40:23-06:00
doi: ""

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-12T10:40:23-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Management of Data (SIGMOD) 2021.
publication_short: SIGMOD 2021
abstract: "DNA sequencing, especially of microbial genomes and metagenomes, has been at the core of recent research advances in large-scale comparative genomics. The data deluge has resulted in exponential growth in genomic datasets over the past years and has shown no sign of slowing down. Several recent attempts have been made to tame the computational burden of sequence search on these terabyte and petabyte-scale datasets, including raw reads and assembled genomes. However, no known implementation provides both fast query and construction time, keeps the low false-positive requirement, and offers cheap storage of the data structure.
We propose a data structure for search called RAMBO (Repeated And Merged BloOm Filter) which is significantly faster in query time than state-of-the-art genome indexing methods- COBS (Compact bit-sliced signature index), Sequence Bloom Trees, HowDeSBT, and SSBT. Furthermore, it supports insertion and query process parallelism, cheap updates for streaming inputs, has a zero false-negative rate, a low false-positive rate, and a small index size. RAMBO converts the search problem into set membership testing among K documents. Interestingly, it is a count-min sketch type arrangement of a membership testing utility (Bloom Filter in our case). The simplicity of the algorithm and embarrassingly parallel architecture allows us to stream and index a 170TB whole-genome sequence dataset in a mere 9 hours on a cluster of 100 nodes while competing methods require weeks. "

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

url_pdf:
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=SeHT1cjIP90&list=PL3xUNnH4TdbsfndCMn02BqAAgGB0z7cwq

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Center"
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
