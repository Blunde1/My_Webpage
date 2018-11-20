+++
title = "Likelihood Estimation of Jump-Diffusions: Extensions from Diffusions to Jump-Diffusions, Implementation with Automatic Differentiation, and Applications"
date = 2016-06-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Berent Å. S. Lunde"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "open access *https://bora.uib.no/handle/1956/18720*"
publication_short = "In *BORA*"

# Abstract and optional shortened version.
abstract = "This thesis considers the problem of likelihood- based parameter estimation for time-homogeneous jump-diffusion processes. The problem is that there often is no analytic solution to the stochastic differential equations driving the process. Thus, the transition density of the process is unknown. In this thesis we build on the solution presented in Preston and Wood (2012), where the transition density of a time- homogeneous diffusion process is approximated by a saddlepoint approximation based on the approximated solution following from discretization schemes, which in turn stems from an Itô-Taylor expansion of the stochastic differential equation. The mathematical tools for understanding the method in Preston and Wood (2012) and the extended methods to jump- diffusions are developed. We reproduce the results found here, and extend the analysis with maximum likelihood estimation for benchmark processes such as the geometric Brownian motion, the Ornstein-Uhlenbeck process, the Cox- Ingersoll-Ross process, and the Merton model. We also investigate the use of the renormalized saddlepoint approximation in the context of maximum likelihood estimation. The implementation of the methods is carried out with the newly released parallel programming package, Template Model Builder, which uses automatic differentiation among other things. We therefore give an introduction to the basics of automatic differentiation in the context of our computational problems, and also extend the Template Model Builder package to e.g. allow for complex numbers. Thereafter we apply the methods developed in previous chapters to the analysis of stock prices modelled as nonlinear stochastic differential equations, with and without jumps. Finally we briefly analyse some models for stochastic volatility."
# abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Computational statistics"]

# Links (optional).
url_pdf = "https://bora.uib.no/bitstream/handle/1956/18720/144736091.pdf?sequence=1&isAllowed=y"
url_preprint = "https://bora.uib.no/handle/1956/18720"
url_code = "#"
url_dataset = "#"
url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

