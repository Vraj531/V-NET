# V-net model on Brain Tumor Segmentation
Volumetric Convolution (Biomedical Image Segmentation)

# Collaborator
Prayushi Mathur, Vraj Patel

This repository contains the file related to Brain Tumor Segmentation using V-net model. The dataset used here is BraTS 2019.

# Introduction
The process of Brain Tumor Segmentation is the process of separating the tumor from normal brain tissues. In the technical terms, this process gives the pixel-wise identification of the type of tumor present in the MRI/CT images. This further can help the doctor to detect the type and location of the tumor in the brain which is challenging task due to irregular form and confusing boundaries of tumors. The results include the following information:
- Loss
- Dice-coefficient

# Introduction Of Files Contained In The Repository
- group_norm.py - This file contains the code of group normalization used in the model.
- model_v.py - This file contains main code of the v-net model.
- v_tr.py - This file contains the methodology code to run the model.

# Model Description
- It is a three dimensional model.
- Input contains 4-channels: t1, t1ce, t2, flair
- Output contains 3 channels: whole tumor, core tumor and enhancing tumor
- It contains residual connections along with skip connections.

# Result
<img src="results/Screenshot from 2019-09-23 15-07-04.png" alt="pic" class="inline"/><br>
