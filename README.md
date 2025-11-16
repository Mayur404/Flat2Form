# Image to Depth & Normal Map Converter

A tool that converts regular images into **depth maps** and **normal maps**. Useful for 3D projects, animation workflows, game development, and general graphics tasks.  
This project uses a deep learning–based image understanding model to estimate pixel-wise geometry from a single image.

## Features
- Generate **depth maps** from input images  
- Generate **surface normal maps**  
- GPU-accelerated inference (if CUDA is available)  
- Works with standard image formats (JPG, PNG, etc.)  
- Simple to run through a Python script or Jupyter notebook  

## Installation

Clone the repository and navigate into the project folder using the `cd` command:


## Installing Requirements
Run:
```bash
pip install -r requirements.txt
```
## Dataset
Download the dataset from the official Hypersim repository: https://github.com/apple/ml-hypersim
## Dataset Structure
The dataset is organized into multiple sets inside the main `dataset` folder.  
Each set contains image frames in the Hypersim naming format, such as:

- `frameXXXX.color.jpg`  
- `frameXXXX.depth_meters.png`  
- `frameXXXX.normal_cam.png`  

Additional files follow the same `frameXXXX.*` pattern used in the Hypersim dataset.
