+++
title = "An information criterion for gradient boosted trees"
date = 2019-10-11T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-09-17T13:00:00
time_end = 2019-09-17T14:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Berent Å. S. Lunde", "Tore S. Kleppe", "Hans J. Skaug"]

# Abstract and optional shortened version.
abstract = "Gradient boosting has been highly successful in machine-learning competitions for structured/tabular data since the introduction of XGBoost in 2014. Gradient boosting may be seen as a way of doing functional gradient descent to the supervised learning problem. As a consequence, in gradient tree boosting, the functional form of the model-ensemble constantly changes during training. To be able to choose the optimal functional complexity, the leading implementations offer a high number of regularization hyperparameters, available for manual tuning. This tuning typically require a combination of computationally costly cross validation on a grid of hyperparameters, coupled with some expert knowledge. To combat this, we propose an information criterion for gradient boosted trees, applicable to both the learning of the topology of trees, and as a stopping criterion for the boosting algorithm. This makes the algorithm adaptive to the dataset at hand; it is completely automatic and with minimal worries of overfitting. Moreover, as the algorithm only has to run once, the computational cost is drastically reduced."

# Name of event and optional event URL.
event = "The stochastics seminar"
event_url = "http://www.ux.uis.no/statistikk/seminar/"

# Location of event.
location = "University of Stavanger, Norway"

# Is this a selected talk? (true/false)
selected = true

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["content/project/GBTorch/GBTorch.md"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Computational statistics", "Boosting", "machine-learning"]

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
