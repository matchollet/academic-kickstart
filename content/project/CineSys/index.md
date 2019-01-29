+++
# Project title.
title = "CineSys"

# Date this page was created.
date = 2019-01-24T00:00:00

# Project summary to display on homepage.
summary = "Automatic Editing of 3D Movies"

# Tags: can be used for filtering projects.
tags = ["CineSys", "Interactive Storytelling"]

# Optional external URL for project (replaces project detail page).
external_link = ""

weight = 4
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = "https://www.youtube.com/watch?v=Aj1Iy_k0QVI"
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = "Automatic 3D Movie Editing Interface"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
  preview_only = true
+++

As part of my Master’s thesis, I proposed a model for automatic editing of 3D movies, that can learn from examples. Using a 3D virtual environment (CineSys) and a description of a scenario (i.e. timed actor actions), it casts the problem of film editing as a path-planning problem in a space of available cameras (pre-defined positions or automatically computed from actors positions). I defined cost functions for shot quality (e.g. shot type preferences, composition, visibility of actions), for cutting between shots (e.g. jump cuts, do not break the line of action), and for pacing. Each rule is associated to a weight: these weights can be automatically learned from manually produced movie examples, effectively representing the editing style of a particular user.

{{< youtube Aj1Iy_k0QVI >}}
