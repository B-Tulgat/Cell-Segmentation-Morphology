# CellPose-Segmentation

## Main Result

- Segmented ~30'000 cell nuclei from 670 images using pretrained SAM-CellPose model (https://pypi.org/project/cellpose).
- Achieved mean IoU of 85.04% and F1 score of 95.86% over 670 bio-images.

<img width="2684" height="1780" alt="image" src="https://github.com/user-attachments/assets/0e4f543b-59f8-4e67-a646-99f28e4d4bea" />


## Dataset
- Description of the biological application
  - This image data set contains a large number of segmented nuclei images and was created for the Kaggle 2018 Data Science Bowl. The image set was a testing ground for the application of novel and cutting edge approaches in computer vision and machine learning to the segmentation of the nuclei belonging to cells from a breadth of biological contexts.
  
- Kaggle 2018 Data Science Bowl: **BBBC038**
  - Link: https://bbbc.broadinstitute.org/BBBC038

- From SAM-Cellpose model predication labels we extracted of 12 morphological features (area, circularity, eccentricity)

<img width="1440" height="929" alt="Cell Segmentation drawio" src="https://github.com/user-attachments/assets/b1561bc6-91f3-4663-a5ba-851f3c6562e1" />

## References

  1. Pachitariu, M., Rariden, M., & Stringer, C. (2025). Cellpose‑SAM: superhuman generalization for cellular segmentation [Preprint]. bioRxiv. [https://doi.org/10.1101/2025.04.28.651001v1](https://doi.org/10.1101/2025.04.28.651001)
