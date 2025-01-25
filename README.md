
# Microscope Image and Dye Sensor Simulation




## Overview
This project generates realistic binary microscope images simulating parasite blobs and their corresponding dye sensor images with patchy dye distribution and leakage effects. The generated images mimic biological microscopy scenarios and can be used for image analysis or machine learning tasks.


## Features

- Microscope Image Generation: Creates a binary image with an irregular black blob (parasite) utilizing ellipse geometry and Gaussian filtering for realism.
- Dye Sensor Image Generation: Simulates sparse dye distribution within the parasite region; includes dye leakage effects outside the parasite region; also adds noise for sensor imperfections.
- Visualization: Displays generated images using Matplotlib.



## Requirements
- Python 3.x
- Required Librarires: numpy, scipy, skimage, matplotlib
Instal dependencies using:
```bash
  pip install numpy scipy scikit-image matplotlib
```
## Usage
- Generate Images: The script generates a binary microscope image (microscope_image) and its corresponding dye sensor image (dye_image).
- Run the script:
```bash
  python microscope_dye_simulation.py
```
- Output: Microscopic and dye sensor images are displayed along with the information if parasite is healthy or cancerous.
