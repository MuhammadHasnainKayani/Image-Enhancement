# Image Upscaling with Real-ESRGAN

## Overview

This script upscales images using the Real-ESRGAN model. It processes images from an input directory, including all subfolders, and saves the upscaled images to a new output directory. Unsupported image formats and CSV files are copied without processing.

## Setup

1. **Install Real-ESRGAN and Dependencies:**

   ```bash
   pip install git+https://github.com/sberbank-ai/Real-ESRGAN.git
   pip install numpy pillow torch
