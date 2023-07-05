# [ICIP 2023] THE ELLIPTIC ENERGY LOSS FOR ROTATED OBJECT DETECTION IN AERIAL IMAGES

<h4 align="center">Cong Zhang<sup>1</sup>, Kunming Luo<sup>2</sup>, Fanman Meng<sup>1</sup>, Qingbo Wu<sup>1</sup></center>
<h4 align="center">1. University of Electronic Science and Technology of China, 2. The Hong Kong University of Science and Technology</center>


## Abstract
Rotated object detection is a promising yet challenging task in computer vision. Existing algorithms mainly train the rotated detector by the $L_n$-norm loss, which is inconsistent with the evaluation metric of Intersection over Union (IoU). However, the concise and efficient solution using the loss based on IoU between oriented boxes is hindered by its non-differentiability.
In this paper, we propose Elliptic Energy Loss, a differentiable loss based on curve energy, to fit with the evaluation metric IoU. Specifically, given a pair of predicted and ground truth boxes, we first convert them to curve representations using the elliptic transformation. Then, the curve energy is calculated to measure the similarity between the predicted and ground truth curves. Finally, the curve energy is used as regression loss to optimize rotated detectors. We conduct experiments with different detectors on DOTA and HRSC2016 datasets, which demonstrate that the performance is significantly improved by our proposed loss. The code is available at https://github.com/zhangc-uestc/EEL.


## Requirements
XXXX

The code will be available soon.


We thank all the authors for their contributions.
