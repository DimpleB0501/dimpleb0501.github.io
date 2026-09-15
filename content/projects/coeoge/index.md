---
title: "UAV Multispectral Imaging for Oil and Water Leak Detection"
weight: 4
date: 2023-04-03
show_date: false
show_date_updated: false
reading_time: false
share: false

card_link: "https://surface-leakage-detection.github.io/"

summary: "UAV multispectral imaging and deep learning for surface oil and water leak detection."

tags:
  - Perception & AI

tech_stack:
  - Python
  - PyTorch
  - YOLOv11
  - RT-DETR
  - Faster R-CNN
  - Multispectral Imaging
  - Deep Learning

links:
  - type: site
    url: "https://surface-leakage-detection.github.io/"
    label: "Website"
  - type: pdf
    url: uploads/multispectral_leak_detection_paper.pdf
    label: "Paper"
  - type: pdf
    url: uploads/multispectral_leak_detection_poster.pdf
    label: "Poster"

featured: true
---
<p align="justify">
Pipeline leakages involving oil and water pose significant environmental and
economic risks, motivating the need for timely and reliable surface leak
detection techniques. This paper presents a proof-of-concept study that
investigates the use of UAV-based multispectral imagery and deep learning for
detecting and distinguishing surface oil and water leaks over soil
backgrounds. Multispectral data were acquired using a UAV-mounted sensor under
controlled experimental conditions and processed through a radiometric and
geometric correction pipeline. Spectral analysis was conducted to assess
band-wise separability, highlighting the effectiveness of Red and Red-Edge
bands for oil–water discrimination. Multiple object detection models,
including YOLOv11, RT-DETR, Faster R-CNN, and a fusion-based YOLOv11-RGBT
variant, were evaluated using these inputs. Experimental results demonstrate
that single-band models achieve robust detection performance, with YOLOv11
attaining detection accuracies of 92.8% for oil and 98.1% for water, while
RT-DETR and Faster R-CNN demonstrated comparable accuracy. The fusion-based
YOLOv11-RGBT model achieved lower performance, likely due to limited dataset
size for effective cross-band feature learning. Overall, the findings
demonstrate that UAV-based multispectral sensing combined with deep learning
offers a practical solution for localized surface leakage monitoring.
</p>
