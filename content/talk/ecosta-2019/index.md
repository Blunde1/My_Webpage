+++
title = "Information criteria for gradient boosted trees: Adaptive tree size and early stopping"
date = 2018-06-20T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-06-26T17:08:35
time_end = 2019-06-26T19:10:15

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Berent Å. S. Lunde", "Tore S. Kleppe", "Hans J. Skaug"]

# Abstract and optional shortened version.
abstract = "In gradient tree boosting, the functional form of the ensemble repeatedly changes during training. To select a sensible functional complexity for the boosting ensemble, the leading implementations offer a high number of hyperparameters for regularization, available for manual tuning. This tuning typically require a combination of computationally costly cross validation, coupled with some expert knowledge. To combat this, we propose an information criterion for gradient boosted trees, applicable to both the learning of the structure of trees, and as a stopping criterion for the boosting algorithm. The resulting algorithm is adaptive to the training data at hand; it is largely automatic and with little worries of overfitting. Moreover, the computations for the criterion require little additional computational overhead, and, as the algorithm only has to run once, the computational cost is drastically reduced in comparison to implementations with manual tuning."

# Name of event and optional event URL.
event = "EcoSta 2019"
event_url = "http://cmstatistics.org/EcoSta2019/index.php"

# Location of event.
location = "National Chung Hsing University, Taiwan"

# Is this a selected talk? (true/false)
selected = false

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
