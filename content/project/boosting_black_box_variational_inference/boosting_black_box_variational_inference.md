+++
# Project title.
title = "Bringing Boosting Black Box Variational Inference to Pyro"

# Date this page was created.
date = 2020-04-05T12:20:00

# Project summary to display on homepage.
summary = "In this project, we contributed an implementation of Boosting Black Box Variational Inference to the Pyro probabilistic programming library."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["probabilistic-programming", "machine-learning"]

# Optional external URL for project (replaces project detail page).
external_link = ""


# Links (optional).
url_pdf = "https://pyro.ai/examples/boosting_bbvi.html"
url_slides = ""
url_video = ""
url_code = "https://github.com/lorenzkuhn/pyro"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
## Abstract:
In collaboration with [Gideon Dresdner](https://scholar.google.com/citations?user=zCsVb4IAAAAJ&hl=en), [Samuel Harrison](https://scholar.google.co.uk/citations?user=SpoKPkgAAAAJ&hl=en) and [Yu Yao](https://www.tnu.ethz.ch/en/team/faculty-and-scientific-staff/dr-yu-yao.html), I implemented the paper [Boosting Black Box Variational Inference](https://arxiv.org/abs/1806.02185) using Pyro. We have contributed [a tutorial](https://pyro.ai/examples/boosting_bbvi.html) to the Pyro documentation to illustrate how to use our implementation.

To quote from the tutorial: "This tutorial demonstrates how to implement boosting black box Variational Inference in Pyro. In boosting Variational Inference, we approximate a target distribution with an iteratively selected mixture of densities. In cases where a single denisity provided by regular Variational Inference doesn’t adequately approximate a target density, boosting VI thus offers a simple way of getting more complex approximations. We show how this can be implemented as a relatively straightforward extension of Pyro’s SVI."

