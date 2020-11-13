---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Efficient Two Step Algorithm for High Dimensional Change Point Regression
  Models Without Grid Search.
subtitle: ''
summary: ''
authors:
- Abhishek Kaul
- Venkata K Jandhyala
- Stergios B Fotopoulos
tags:
- '"Change point regression"'
- '"High dimensional models"'
- '"L1-L0regularization"'
- '"Rate of convergence"'
- '"Two phase regression"'
categories: []
date: '2019-01-01'
lastmod: 2020-11-12T20:43:21-08:00
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
publishDate: '2020-11-13T04:43:21.311638Z'
publication_types:
- '2'
abstract: We propose a two step algorithm based on $ell_1/ell_0$ regularization for
  the detection and estimation of parameters of a high dimensional change point regression
  model and provide the corresponding rates of convergence for the change point as
  well as the regression parameter estimates. Importantly, the computational cost
  of our estimator is only $2·p$Lasso$(n,p)$, where Lasso$(n,p)$ represents the computational
  burden of one Lasso optimization in a model of size $(n,p)$. In comparison, existing
  grid search based approaches to this problem require a computational cost of at
  least $n· m̊ Lasso(n,p)$ optimizations. Additionally, the proposed method is shown
  to be able to consistently detect the case of `no change', i.e., where no finite
  change point exists in the model. We work under a subgaussian random design where
  the underlying assumptions in our study are milder than those currently assumed
  in the high dimensional change point regression literature. We allow the true change
  point parameter $τ_0$ to possibly move to the boundaries of its parametric space,
  and the jump size $|b_0-g_0|_2$ to possibly diverge as $n$ increases. We then characterize
  the corresponding effects on the rates of convergence of the change point and regression
  estimates. In particular, we show that, while an increasing jump size may have a
  beneficial effect on the change point estimate, however the optimal rate of regression
  parameter estimates are preserved only upto a certain rate of the increasing jump
  size. This behavior in the rate of regression parameter estimates is unique to high
  dimensional change point regression models only. Simulations are performed to empirically
  evaluate performance of the proposed estimators. The methodology is applied to community
  level socio-economic data of the U.S., collected from the 1990 U.S. census and other
  sources.
publication: '*Journal of Machine Learning Research*'
url_pdf: media/jmlr.pdf
---
