---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Analysis of microbiome data in the presence of excess zeros
subtitle: ''
summary: ''
authors:
- Abhishek Kaul
- Siddhartha Mandal
- Ori Davidov
- Shyamal D Peddada
tags:
- '"Microbiome data"'
- '"Aitchisons log-ratio"'
- '"bootstrap"'
- '"covariates"'
- '"cross-sectional data"'
- '"false discovery rate (FDR)"'
categories: []
date: '2017-01-01'
lastmod: 2020-11-12T20:43:22-08:00
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
publishDate: '2020-11-13T04:43:22.432229Z'
publication_types:
- '2'
abstract: 'Motivation: An important feature of microbiome count data is the presence
  of a large number of zeros. A common strategy to handle these excess zeros is to
  add a small number called pseudo-count (e.g., 1). Other strategies include using
  various probability models to model the excess zero counts. Although adding a pseudo-count
  is simple and widely used, as demonstrated in this paper, it is not ideal. On the
  other hand, methods that model excess zeros using a probability model often make
  an implicit assumption that all zeros can be explained by a common probability models.
  As described in this article, this is not always recommended as there are potentially
  three types/sources of zeros in a microbiome data. The purpose of this paper is
  to develop a simple methodology to identify and accomodate three different types
  of zeros and to test hypotheses regarding the relative abundance of taxa in two
  or more experimental groups. Another major contribution of this paper is to perform
  constrained (directional or ordered) inference when there are more than two ordered
  experimental groups (e.g., subjects ordered by diet or age groups or environmental
  exposure groups). As far as we know this is the first paper that addresses such
  problems in the analysis of microbiome data.  Results: Using extensive simulation
  studies, we demonstrate that the proposed methodology not only controls the false
  discovery rate at a desired level of significance while competing well in terms
  of power with DESeq2, a popular procedure derived from RNASeq literature. As expected,
  the method using pseudo-counts tends to be very conservative and the classical t-test
  that ignores the underlying simplex structure in the data has an inflated FDR.'
publication: '*Frontiers in microbiology*'
url_pdf: media/zeros.pdf
doi: 10.3389/fmicb.2017.02114
---
