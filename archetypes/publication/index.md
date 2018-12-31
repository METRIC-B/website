+++
title = "{{ replace .Name "-" " " | title }}"
date = {{ .Date }}
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [""]

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

# Journal name
publication = ""

# Abstract
abstract = ""

# Is this a selected publication? (true/false)
selected = false

# People (optional).
#   Associate this publication with one or more people.
#   Simply enter the persons name as used by the website
#   E.g. `projects = ["tomhardwicke"]` references 
#   `content/people/tomhardwicke/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
url_custom = [
{name = "DOI", url = ""}
{name = "PDF", url = ""},
{name = "Preprint", url = ""},
{name = "Pre-registration", url = ""},
{name = "Data", url = ""},
{name = "Materials", url = ""},
{name = "AnalysisCode", url = ""},
{name = "ReproducibleContainer", url = ""},
{name = "Commentary", url = ""}
]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
