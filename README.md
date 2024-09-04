# Image Upscaling with Real-ESRGAN

## Overview

This script upscales images using the Real-ESRGAN model. It processes images from an input directory, including all subfolders, and saves the upscaled images to a new output directory. Unsupported image formats and CSV files are copied without processing.
You just need to specify the input folder path and define the threshold for image dimensions. When you run the code, the output folder will contain:

Images that are above the threshold size, copied as-is.
Images that are below the threshold size, scaled by the Real-ESRGAN model.


## Setup

1. **Install Real-ESRGAN and Dependencies:**

   ```bash
   pip install git+https://github.com/sberbank-ai/Real-ESRGAN.git
   pip install numpy pillow torch
