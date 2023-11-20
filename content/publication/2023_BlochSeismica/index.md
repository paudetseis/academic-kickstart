+++
title = "PyRaysum: Software for Modeling Ray-theoretical Plane Body-wave Propagation in Dipping Anisotropic Media"
date = 2023-02-15

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wasja Bloch", "admin"]

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
publication = "*Seismica*"
publication_short = ""

# Abstract.
abstract = "This article introduces PyRaysum, a Python software for modeling ray-theoretical body-wave propagation in dipping and/or anisotropic layered media based on the popular Fortran code Raysum. We improve and expand upon Raysum in several ways: 1) we significantly reduce the overhead by avoiding I/O operations; 2) we implement automatic phase labeling to facilitate the interpretation of complex seismograms; 3) we provide the means to correct inaccuracies in the calculated amplitude of free surface reverberations. We take advantage of the modern, object-oriented Python environment to offer various classes and methods to perform receiver function calculation, filtering and plotting. PyRaysum also integrates well with NumPy and ObsPy, two standard libraries for numerical computing and seismology. PyRaysum is built in Python version 3 and requires a Fortran compiler, but otherwise runs on all platforms. The software offers a high-level, ease-of-use user interface and is equipped with complete documentation and testing as well as tutorials to reproduce published examples from the literature. Time-optimized post-processing functions allow for the straightforward and efficient incorporation of PyRaysum synthetic data into optimization or probabilistic parametric search approaches."

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.26443/seismica.v2i1.220"

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
projects = []

# Links (optional).
url_pdf = ""
url_code = "https://github.com/paudetseis/PyRaysum"
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
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++