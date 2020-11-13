---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Pivotal estimation via self-normalization for high-dimensional linear models
  with error in variables
subtitle: ''
summary: ''
authors:
- Alexandre Belloni
- Abhishek Kaul
- Mathieu Rosenbaum
tags:
- '"pivotal estimation"'
- '"self-normalized sums"'
- '"error in measurement"'
- '"highdimensional models"'
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
publishDate: '2020-11-13T04:43:21.855698Z'
publication_types:
- '2'
abstract: We propose a new estimator for the high-dimensional linear regression model
  with observation error in the design where the number of coefficients is potentially
  larger than the sample size. The main novelty of our procedure is that the choice
  of penalty parameters is pivotal. The estimator is based on applying a self-normalization
  to the constraints that characterize the estimator. Importantly, we show how to
  cast the computation of the estimator as the solution of a convex program with second
  order cone constraints. This allows the use of algorithms with theoretical guarantees
  and reliable implementation. Under sparsity assumptions, we derive $ell_q$-rates
  of convergence and show that consistency can be achieved even if the number of regressors
  exceeds the sample size. We further provide a simple to implement rule to threshold
  the estimator that yields a provably sparse estimator with similar $ell_2$ and $ell_1$-rates
  of convergence. The thresholds are data-driven and component dependents. Finally,
  we also study the rates of convergence of estimators that refit the data based on
  a selected support with possible model selection mistakes. In addition to our finite
  sample theoretical results that allow for non-i.i.d. data, we also present simulations
  to compare the performance of the proposed estimators.
publication: '*arXiv preprint arXiv:1708.08353*'
url_pdf: media/pivotal.pdf
---
