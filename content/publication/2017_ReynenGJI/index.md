+++
title = "Supervised machine learning on a network scale: application to seismic event classification and detection"
date = 2017-05-31

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["reynen", "admin"]

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
publication = "*Geophysical Journal International*"
publication_short = ""

# Abstract.
abstract = """
A new method using a machine learning technique is applied to event classification and detection at seismic networks. This method is applicable to a variety of network sizes and settings. The algorithm makes use of a small catalogue of known observations across the entire network. Two attributes, the polarization and frequency content, are used as input to regression. These attributes are extracted at predicted arrival times for P and S waves using only an approximate velocity model, as attributes are calculated over large time spans. This method of waveform characterization is shown to be able to distinguish between blasts and earthquakes with 99 per cent accuracy using a network of 13 stations located in Southern California. The combination of machine learning with generalized waveform features is further applied to event detection in Oklahoma, United States. The event detection algorithm makes use of a pair of unique seismic phases to locate events, with a precision directly related to the sampling rate of the generalized waveform features. Over a week of data from 30 stations in Oklahoma, United States are used to automatically detect 25 times more events than the catalogue of the local geological survey, with a false detection rate of less than 2 per cent. This method provides a highly confident way of detecting and locating events. Furthermore, a large number of seismic events can be automatically detected with low false alarm, allowing for a larger automatic event catalogue with a high degree of trust."""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1093/gji/ggx238"

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
projects = ["DataScience"]

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