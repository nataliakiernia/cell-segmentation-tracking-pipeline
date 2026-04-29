# cell-segmentation-tracking-pipeline

Cell Segmentation and Tracking Pipeline 

This repository contains an end-to-end pipeline for cell segmentation and tracking in time-resolved microscopy data, integrating preprocessing, Cellpose-based instance segmentation, and Ultrack tracking.

This repository is intended to support reproducibility and provide a starting point for applying segmentation and tracking pipelines to new biological datasets.

🚧 THIS REPOSITORY IS CURRENTLY UNDER CONSTRUCTION 🚧

I am still in the process of adding the necessary files and organizing the codebase. Once the repository is complete, this notice will be removed.

How to Run:

git clone https://github.com/nataliakiernia/cell-segmentation-tracking-pipeline.git 
cd cell-segmentation-tracking-pipeline
pip install -r requirements.txt

Note:
Uses Cellpose for instance segmentation and Ultrack for tracking
Designed for time-resolved microscopy data (.tif or .zarr)
Includes a separate 2D U-Net study for foreground segmentation (not used in pipeline)

Future Work:
3D segmentation (U-Net)
Quantitative evaluation (IoU, TRA, DET)
Improved scalability and annotation tools
