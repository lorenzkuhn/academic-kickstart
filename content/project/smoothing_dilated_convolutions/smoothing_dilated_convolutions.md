+++
# Project title.
title = "Efficient Smoothing of Dilated Convolutions for Image Segmentation"

# Date this page was created.
date = 2019-03-07T11:43:00

# Project summary to display on homepage.
summary = "In this project we introduce low cost methods of improving dilated convolutions in an image segmentation application. We achieve comparable results to state-of-the-art segmentation performance  while being computationally more efficient than previously proposed methods."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Deep Learning", "Machine Learning", "Image Segmentation"]

# Optional external URL for project (replaces project detail page).
external_link = ""


# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = "https://github.com/lorenzkuhn/Efficient-Smoothing-of-Dilated-Convolutions"

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
Course project for Deep Learning at ETH Zurich in the fall of 2018 in collaboration with Konstantin Donhauser, Manuel Fritsche and Thomas Ziegler. 


## Abstract:

 Dilated Convolutions have been shown to be highly useful for the task of image segmentation.
By introducing gaps into convolutional filters, they enable the use of larger receptive fields without increasing the original kernel size. Even though this allows for the inexpensive capturing of features at different scales, the structure of the dilated convolutional filter leads to a loss of information.

We hypothesise that inexpensive modifications to Dilated Convolutional Neural Networks, such as additional averaging layers, could overcome this limitation. In this project we test this hypothesis by evaluating the effect of these modifications for a state-of-the art image segmentation system and compare them to existing approaches with the same objective. 

Our experiments show that our proposed methods improve the performance of dilated convolutions for image segmentation. Crucially, our modifications achieve these results at a much lower computational cost than previous smoothing approaches.
