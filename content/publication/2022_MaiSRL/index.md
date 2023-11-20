+++
title = "QuakeLabeler: a fast seismic data set creation and annotation toolbox for AI applications"
date = 2022-03-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["mai", "admin"]


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
publication = "*Seismological Research Letters*"
publication_short = ""

# Abstract.
abstract = """
The production and preparation of data sets are essential steps in machine learning (ML) applications. With the increasing volume and scale of available ML techniques in seismology, annotating seismograms or seismic features has become time consuming and tedious for many researchers. Furthermore, most methods train and validate on unique data subsets, which hampers independent performance evaluation and comparison. To address this problem, we have developed the software QuakeLabeler, an open‐source Python package to customize, build, and manage earthquake training data sets, including processing and visualization. QuakeLabeler has tight pipeline functions, which include retrieving seismograms from multiple online data centers, querying online human‐reviewed catalogs, signal processing, annotating (labeling), and analyzing data distribution. In addition, relevant statistical graphics and human‐readable output files can be generated. Various file export formats are supported, such as Seismic Analysis Code (.sac), mini Standard for Exchange of Earthquake Data (.mseed), NumPy (.npz), MATLAB (.mat), and the Hierarchical Data Format version 5 (.hdf5). This toolbox is packaged with an interactive command‐line interface. Three alternative running modes (beginner, advanced, and benchmark) are implemented, intended to offer specific data set solutions for different types of applications, that is, quick‐start recipes for simple ML solutions, advanced design for customized project training, and benchmark bulletins for model comparison.
"""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1785/0220210290"

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