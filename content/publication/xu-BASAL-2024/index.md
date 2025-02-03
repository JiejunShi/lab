---
# Documentation: https://wowchemy.com/docs/managing-content/

title: BASAL - a universal mapping algorithm for nucleotide base-conversion sequencing
subtitle: ''
summary: ''
authors:
- Moping Xu
- Xiaoyang Liu
- Miao Wang
- Tingting Luo
- Yawei Gao
- Jun Liu
- Jiejun Shi
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
tags:
- RNA Modification
- DNA Modification
- Reads Aligner

categories: []
date: '2024-12-01'
lastmod: 2025-01-02T17:57:52+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-12-01T17:57:52+08:00'
publication_types:
- '2'
abstract: Utilizing base-conversion (BC) techniques, single-base resolution profiling of RNA and DNA 
  modifications has significantly advanced. BC strategies range from one-way conversions (e.g. 
  cytosine-to-thymine for 5-methylcytosine, adenine-to-guanine for N6-methyladenosine), to 
  multi-way conversions (e.g. adenine to cytosine/guanine/thymine for N1-methyladenosine) and 
  deletion-induced conversions (e.g. pseudouridine-to-deletion). Existing sequence aligners 
  struggle with these diverse conversions, often leading to misaligning or inefficiency. We 
  introduce BASAL (BAse-conversion Sequencing ALigner), which leverages bit-masking technology 
  to accurately calculate mismatch penalties and supports all BC strategies. BASAL outperforms 
  state-of-the-art tools in both mapping accuracy and efficiency. Through simulated and real 
  data testing, along with experimental validation, we demonstrate that BASAL excels at 
  identifying reliable modification sites. Moreover, BASAL enhances single-cell m6A analysis, 
  revealing cell subpopulations and a cell evolutionary direction that align with biological 
  functions, which other aligners fall short. BASAL's versatility establishes it as a universal 
  aligner for RNA and DNA modification sequencing, facilitating groundbreaking discoveries in 
  epigenomics and epitranscriptomics.
publication: '*Nucleic Acids Research*'
doi: 10.1093/nar/gkae1201
links:
- name: URL
  url: https://academic.oup.com/nar/article-lookup/doi/10.1093/nar/gkae1201
---
