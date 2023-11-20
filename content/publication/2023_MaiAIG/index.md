+++
title = "Blockly earthquake transformer: A deep learning platform for custom phase picking"
date = 2023-11-01

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["mai", "admin", "Claire C. K. Perry", "S. Mousavi", "zhang"]


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
publication = "*Artificial Intelligence in Geosciences*"
publication_short = ""

# Abstract.
abstract = """
Deep-learning (DL) algorithms are increasingly used for routine seismic data processing tasks, including seismic event detection and phase arrival picking. Despite many examples of the remarkable performance of existing (i.e., pre-trained) deep-learning detector/picker models, there are still some cases where the direct applications of such models do not generalize well. In such cases, substantial effort is required to improve the performance by either developing a new model or fine-tuning an existing one. To address this challenge, we present Blockly Earthquake Transformer(BET), a deep-learning platform for efficient customization of deep-learning phase pickers. BET implements Earthquake Transformer as its baseline model, and offers transfer learning and fine-tuning extensions. BET provides an interactive dashboard to customize a model based on a particular dataset. Once the parameters are specified, BET executes the corresponding phase-picking task without direct user interaction with the base code. Within the transfer-learning module, BET extends the application of a deep-learning P and S phase picker to more specific phases (e.g., Pn, Pg, Sn and Sg phases). In the fine-tuning module, the model performance is enhanced by customizing the model architecture. This no-code platform is designed to quickly deploy reusable workflows, build customized models, visualize training processes, and produce publishable figures in a lightweight, interactive, and open-source Python toolbox.
"""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = "10.1016/j.aiig.2023.05.003"

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
url_code = "https://github.com/maihao14/BlocklyEQTransformer"
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