---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "What Limits Agentic Systems Efficiency?"
authors: [Song Bian*, Minghao Yan*, Anand Jayarajan, Gennady Pekhimenko, Shivaram Venkataraman]
date: 2025-10-18T10:40:23-06:00
doi: ""

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

# Schedule page publish date (NOT publication's date).
publishDate: 2025-10-18T10:40:23-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication:
publication_short: Arxiv
abstract: "Large Language Models (LLMs), such as OpenAI-o1 and DeepSeek-R1, have demonstrated strong reasoning capabilities. To further enhance LLM capabilities, recent agentic systems, such as Deep Research, incorporate web interactions into LLM reasoning to mitigate uncertainties and reduce potential errors. However, existing research predominantly focuses on reasoning performance, often neglecting the efficiency of agentic systems. In this work, we present a comprehensive empirical study that identifies efficiency bottlenecks in web-interactive agentic systems. We decompose end-to-end latency into two primary components: LLM API latency and web environment latency. We conduct a comprehensive empirical study across 15 models and 5 providers to demonstrate high variability in API-based agentic systems. We observe that web environment latency can contribute as much as 53.7% to the overall latency in a web-based agentic system. To improve latency, we propose SpecCache, a caching framework augmented with speculative execution that can reduce web environment overhead. Extensive evaluations on two standard benchmarks show that our approach improves the cache hit rate by up to 58× compared to a random caching strategy, while reducing web environment overhead by up to 3.2×, without degrading agentic system performance."
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

url_pdf: https://arxiv.org/pdf/2510.16276
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
