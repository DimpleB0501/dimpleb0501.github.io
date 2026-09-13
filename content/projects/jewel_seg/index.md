---
title: "Jewellery Segmentation"
weight: 12
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

summary: "Analysis and implementation of image segmentation algorithms for automatic jewellery background removal."

tags:
  - Perception & AI

tech_stack:
  - C++
  - OpenCV
  - Image Segmentation
  - Computer Vision

links: []

featured: true
---

<p align="justify">
In digital image processing and computer vision, image segmentation is the process
of partitioning a digital image into multiple segments. It simplifies image
analysis by assigning labels to different regions, which can support subsequent
object detection and image-processing tasks.
</p>

<p align="justify">
I worked as a Project Assistant at the Multimodal Perception Laboratory,
International Institute of Information Technology, Bangalore, where I analyzed
different image segmentation algorithms and developed an algorithm for segmenting
the background of shared jewellery images.
</p>

<p align="justify">
The objective was to replace the original background with a transparent
background, allowing vendors to further edit the images and prepare them for
use on online selling platforms.
</p>

<p align="justify">
Figures 1 and 2 show the performance of the segmentation algorithm on original
images provided by the vendors.
</p>

<figure>
    <img src="a_good.png"
         alt="Jewellery segmentation best case">
    <figcaption>
        Figure 1: Segmentation algorithm — best case
    </figcaption>
</figure>

<figure>
    <img src="b_bad.png"
         alt="Jewellery segmentation worst case">
    <figcaption>
        Figure 2: Segmentation algorithm — worst case
    </figcaption>
</figure>
