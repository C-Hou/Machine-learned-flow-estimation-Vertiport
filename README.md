# Overview

Overview
This repository accompanies the article titled "Machine-learned flow estimation with sparse data --- exemplified for the rooftop of an unmanned aerial vehicle vertiport" by Chang Hou, Luigi Marra, Guy Y. Cornejo Maceda, Peng Jiang, Jingguo Chen, Yutong Liu, Gang Hu, Jialong Chen, Andrea Ianiro, Stefano Discetti, Andrea Meilán-Vila and Bernd R. Noack.

This paper enables extrapolation of wind conditions far beyond the training data, and is exemplified for the flow above an Unmanned Aerial Vehicle (UAV) vertiport.

# Paper Information
Title: Machine-learned flow estimation with sparse data --- exemplified for the rooftop of an unmanned aerial vehicle vertiport
Authors: Chang Hou, Luigi Marra, Guy Y. Cornejo Maceda, Peng Jiang, Jingguo Chen, Yutong Liu, Gang Hu, Jialong Chen, Andrea Ianiro, Stefano Discetti, Andrea Meilán-Vila and Bernd R. Noack
Journal: Physics of Fluids
Year: 2024
DOI: https://doi.org/...

# Functions Overview
mainVertiportFowEstimation.m

Main body of the frame work, examplified by the leading POD modes of the vertiport flow data.
IsoMap.m

Applies ISOMAP for manifold learning.
isomap_decoder.m

Performs a Knn interpolation to transition from manifold coordinates to snapshots as proposed by Farzamnik E, Ianiro A, Discetti S, et al. in "From snapshots to manifolds – a tale of shear flows."
KNN_projection.m

Performs a Knn process

WindConditionEstimator.m
Perform the wind speed estimation based on sensor signal



# Contact Information
Email: houchangqaz@qq.com

# Issues and Feedback
If you encounter any issues or have feedback regarding this code, please open an issue on our GitHub repository. Your insights and suggestions are valuable and appreciated.
