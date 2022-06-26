## Problem Statement :

[MPII Human Pose dataset](http://human-pose.mpi-inf.mpg.de/#) is a state of the art benchmark for evaluation of articulated human pose estimation. The dataset includes around 25K images containing over 40K people with annotated body joints.

Although many experiments use neural networks to achieve the classification, some stakeholders demand better explainability.

Here we have a small subset of mpii's annotated data, filtered to include positions related to sports and exercise. The challenge here is to use just the annotations (and not the images) for pose classification.

- Machine Learning Task: **Classification**
- Target Variable: **Activity name**
- Evaluation Metric - choose the best !

## Data Description :

|     | Columns  | Description   |
|----:|:--------|:--------|
|  0 | img_id | image id  |
|  0 | rx1, ry1, rx2, ry2 | coordinates of the head rectangle  |
|  1 | scale | person scale w.r.t. 200 px height  |
|  6  | x_i, y_i  | keypoint coordinates of the ith joint |
|  6  | vis_i  | visibility of the ith joint   | 
| 5 | act_name | activity name |
| 4 | cat_name | category name |

Explain the task:
