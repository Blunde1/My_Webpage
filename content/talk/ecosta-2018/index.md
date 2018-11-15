+++
title = "Saddlepoint adjusted inversion of characteristic functions"
date = 2018-06-20T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2018-06-20T17:08:30
time_end = 2018-06-20T19:09:50

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Berent Å. S. Lunde", "Tore S. Kleppe", "Hans J. Skaug"]

# Abstract and optional shortened version.
abstract = "For certain types of statistical models, the characteristic function (Fourier transform) is available in closed form, whereas the probability density function has an intractable form, typically as an infinite sum of probability weighted densities. Important such examples include solutions of stochastic differential equations with jumps, the Tweedie model, and Poisson mixture models. We propose a novel and general numerical method for retrieving the probability density function from the characteristic function. Unlike methods based on direct application of quadrature to the inverse Fourier transform, the proposed method allows accurate evaluation of the log-probability density function arbitrarily far out in the tail. Moreover, unlike saddlepoint approximations, the proposed methodology can be made arbitrarily accurate. Owing to these properties, the proposed method is computationally stable and very accurate under log-likelihood optimisation. The method is illustrated for a normal variance-mean mixture, and in an application of maximum likelihood estimation to a jump diffusion model for financial data."
abstract_short = "EcoSta conference in Hong Kong, presentation on saddlepoint adjusted inversion of characteristic functions"

# Name of event and optional event URL.
event = "EcoSta 2018"
event_url = "http://cmstatistics.org/EcoSta2018/index.php"

# Location of event.
location = "City University, Hong Kong"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["content/project/ExactSPA/ExactSPA.md"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Computational statistics"]

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides = "mlmeetup/mlmeetup_presentation_bl"
#slides = ""

# Links (optional).
url_pdf = ""
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
