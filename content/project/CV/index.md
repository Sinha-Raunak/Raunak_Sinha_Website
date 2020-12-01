---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Monocular SLAM"
summary: ""
authors: []
tags: []
categories: []
date: 2018-05-06T20:24:33+05:30

# Optional external URL for project (replaces project detail page).

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://drive.google.com/file/d/1-eZLcVXJHvwwvomqvd8zr5NItWAwjQ5N/view?usp=sharings"



---

Simultaneous location and mapping(SLAM) is the problem of creating a map of an unknown environment and simultaneously tracking agent’s location. Concepts of epipolar geometry give multi-view solution for this problem. Monocular SLAM is performing this task with a single camera. As simple hardware can be utilized, this reduces cost and hardware complexity. Multiple algorithms and benchmark datasets have been developed for studying this problem. Application of Monocular SLAM extend to domains like robotics, entertainment augmented reality), telepresence and more. 
We explore various monocular SLAM algorithms: Parallel Tracking and Mapping(PTAM), Large-Scale Direct Monocular(LSD)SLAM and ORB-SLAM.
Initial Proposal: We would focus on evaluating performance on benchmark datasets and analyzing the results. We plan to use the algorithm with best performance on the benchmark dataset, on real-time data.
Updated proposal (after feedback): We would focus on analyzing the results of our algorithm on varying sequences (chosen from a benchmark dataset: TUM RGB-D so as to allow enough variations - we only use the RGB component of the data) and understand the successes and failure cases of our model.
