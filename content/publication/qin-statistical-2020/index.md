---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Statistical Assessment of Depth Normalization for Small RNA Sequencing
subtitle: ''
summary: ''
authors:
- Li-Xuan Qin
- Jian Zou
- Jiejun Shi
- Ann Lee
- Aleksandra Mihailovic
- Thalia A. Farazi
- Thomas Tuschl
- Samuel Singer
tags:
- Algorithms
- Benchmarking
- Humans
- Sequence Analysis
- RNA
categories: []
date: '2020-06-01'
lastmod: 2022-01-02T17:57:54+08:00
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
publishDate: '2022-01-02T09:57:54.038351Z'
publication_types:
- '2'
abstract: 'PURPOSE: Methods for depth normalization have been assessed primarily with
  simulated data or cell-line-mixture data. There is a pressing need for benchmark
  data enabling a more realistic and objective assessment, especially in the context
  of small RNA sequencing. METHODS: We collected a unique pair of microRNA sequencing
  data sets for the same set of tumor samples; one data set was collected with and
  the other without uniform handling and balanced design. The former provided a benchmark
  for evaluating evidence of differential expression and the latter served as a test
  bed for normalization. Next, we developed a data perturbation algorithm to simulate
  additional data set pairs. Last, we assembled a set of computational tools to visualize
  and quantify the assessment. RESULTS: We validated the quality of the benchmark
  data and showed the need for normalization of the test data. For illustration, we
  applied the data and tools to assess the performance of 9 existing normalization
  methods. Among them, trimmed mean of M-values was a better scaling method, whereas
  the median and the upper quartiles were consistently the worst performers; one variation
  of remove unwanted variation had the best chance of capturing true positives but
  at the cost of increased false positives. In general, these methods were, at best,
  moderately helpful when the level of differential expression was extensive and asymmetric.
  CONCLUSION: Our study (1) provides the much-needed benchmark data and computational
  tools for assessing depth normalization, (2) shows the dependence of normalization
  performance on the underlying pattern of differential expression, and (3) calls
  for continued research efforts to develop more effective normalization methods.'
publication: '*JCO clinical cancer informatics*'
doi: 10.1200/CCI.19.00118
---
