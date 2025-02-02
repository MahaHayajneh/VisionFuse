# VisionFuse: A MATLAB Tool for Image Processing & Registration

## Overview
VisionFuse is a MATLAB-based tool tailored for advanced image processing and registration tasks. It integrates several techniques like noise reduction, intensity normalization, image resampling, and artifact removal, alongside feature-based methods such as SURF, SIFT, and ORB, and intensity-based methods including NCC, MI, and MMI.

## Key Features
- **Noise Reduction:** Use filters like Gaussian, Median, and Non-local means.
- **Intensity Normalization:** Apply Histogram Matching and Contrast Stretching.
- **Image Resampling:** Resize or rotate images as needed.
- **Artifact Removal:** Minimize or eliminate artifacts from your images.
- **Feature-Based Methods:** Detect key features using SURF, SIFT, and ORB.
- **Intensity-Based Methods:** Perform image registration using NCC, MI, and MMI.

## Requirements
To ensure proper functionality of VisionFuse, the following MATLAB toolboxes are necessary:
- Image Processing Toolbox
- Computer Vision Toolbox

Additionally, the **VLFeat** library is required for SIFT feature extraction and should be installed separately.

## Installation Instructions
1. Download or clone the VisionFuse repository to your machine.
2. Confirm the installation of the required MATLAB toolboxes.
3. Open and run the `VisionFuse.mlapp` file in MATLAB.

## How to Use
- **Import Images:** Use the buttons in the app to load your images.
- **Select Processing Methods:** Choose from various available techniques and adjust their settings.
- **View Results:** The processed images will be displayed in the output axes.
