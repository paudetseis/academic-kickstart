+++
title = "Automatic detection and location of seismic events from time-delay projection mapping and neural network classification"
date = 2020-09-22

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["mosher", "admin"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Journal of Geophysical Research*"
publication_short = ""

# Abstract.
abstract = """
The past several decades have seen an exponential increase in the volume of available seismic data, and with it has come the need to develop fast, automatic earthquake detection, and location algorithms. Some of the most recent and promising tools come from the field of machine learning. In this study, we combine a recent seismic detection and location method with neural network classification and analyze 4 months of continuous data recorded by a network of 76 stations in northern California. While these approaches have been used separately, our implementation is unique in that it is not constrained by source templates and avoids user‐defined detection thresholds. In particular, we partition our data set into 234,240, 3‐min long time windows with 75% overlap. For each time window, we create a 3D image that captures information about the coherence of the seismic wavefield. We then devise four features as input and train a neural network classifier to predict which time windows in the data set are likely to contain regional seismic events. These features include the second and fourth Hu image moments computed from 2D cross sections of our 3D images and statistical p values that quantify the probability of observing network‐wide power‐spectral density values at 0.2 and 0.5 s. Our neural network model predicts that 2,522 time windows contain seismic events, from which we locate 1,192 unique events."""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1029/2020JB019426"

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["SubductionZones"]

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{name = "Citations: 9", url = "https://scholar.google.com/scholar?cites=4825604373906396874"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++