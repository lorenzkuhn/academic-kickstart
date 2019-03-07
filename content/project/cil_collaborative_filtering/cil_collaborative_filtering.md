+++
# Project title.
title = "Collaborative Filtering: Stacking Collaborative Filtering and Neural Networks for Improved Recommendations"

# Date this page was created.
date = 2019-03-07T11:07:00

# Project summary to display on homepage.
summary = "For this proejct we leverage matrix factorization and gradient descent approaches to build a recommender system for movies."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Deep Learning", "Machine Learning", "Collaborative Filtering"]

# Optional external URL for project (replaces project detail page).
external_link = ""


# Links (optional).
url_pdf = "https://sea-region.github.com/kkleindev/CILRecommender2018/blob/master/report/report.pdf"
url_slides = ""
url_video = ""
url_code = "https://sea-region.github.com/kkleindev/CILRecommender2018/tree/master/"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/georgecushen"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by rawpixel on Unsplash"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
Course project for Computational Intelligence Lab at ETH Zurich in the spring of 2018. 

## Abstract:

Online businesses face the challenge of recommending relevant products to users based on users' previous preferences and similar customers. This work explores the use of classic matrix factorization methods on the one hand and recent neural network-based methods on the other hand. Final predictions were further improved using ensembling methods such as bagging and stacking.
We report similar, competitive scores for matrix factorization methods and slightly lower accuracy for neural network-based methods with a final ensemble RMSE of 0.964.

My team mate, Kevin Klein, nicely summarises his main insights [here](http://kevinkle.in/jekyll/update/2018/07/10/cf-mf.html).