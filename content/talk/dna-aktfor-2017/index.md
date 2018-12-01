+++
title = "Likelihood Estimation of Jump-Diffusions: Extensions from Diffusions to Jump-Diffusions, Implementation with Automatic Differentiation, and Applications"
date = 2017-02-16T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2017-02-16T17:18:00
time_end = 2017-02-16T19:19:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Berent Å. S. Lunde"]

# Abstract and optional shortened version.
abstract = "This lecture considers the problem of likelihood-based parameter estimation for time-homoge- neous jump-diffusion processes. The problem is that there often is no analytic solution to the stochastic differential equations driving the process. Thus, the transition density of the process is unknown. We build on the solution presented in [Preston & Wood 2012], where the transition density of a time-homogeneous diffusion process is approximated by a saddlepoint approximation based on the approximated solution following from discretization schemes, which in turn stems from an Itô-Taylor expansion of the stochastic differential equation. The mathematical tools for understanding the method in [Preston & Wood 2012] and the extended methods to jump-diffusions are developed. We reproduce the results found here, and extend the analysis with maximum likelihood estimation for benchmark processes such as the geometric Brownian motion, the Ornstein-Uhlenbeck process, the Cox-Ingersoll-Ross process, and the Merton model. We also investigate the use of the renormalized saddlepoint approximation in the context of maximum likelihood estimation. The implementation of the methods is carried out with the newly released parallel programming package, Template Model Builder, which uses automatic differentiation among other things. We therefore give an introduction to the basics of automatic differentiation in the context of our computational problems, and also extend the Template Model Builder package to e.g. allow for complex numbers. Thereafter we apply the methods developed in previous chapters to the analysis of stock prices modelled as nonlinear stochastic differential equations, with and without jumps. Finally we briefly analyse some models for stochastic volatility."
abstract_short = "Lecture after winning Aktuarprisen 2017"

# Name of event and optional event URL.
event = "Aktuarfokus"
event_url = "http://aktfor.no/foiler-fra-aktuarfokus-16-02-2017/"

# Location of event.
location = "Scandic, Oslo, Norway"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Computational statistics", "Quantitative finance"]

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "mlmeetup/mlmeetup_presentation_bl"
#slides = "dna-spring-2018"

# Links (optional).
url_pdf = "http://aktfor.no/wp-content/uploads/2017/02/Likelihood-Estimation-of-Jump-Diffusions-Berent.pdf"
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

Slides for the presentation can be found at [here](http://aktfor.no/wp-content/uploads/2017/02/Likelihood-Estimation-of-Jump-Diffusions-Berent.pdf).