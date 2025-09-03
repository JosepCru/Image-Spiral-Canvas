# Image-Spiral-Canvas

A lightweight Python library to assemble image mosaics in a spiral pattern.  
Uses NumPy for pixel manipulation and OpenCV for image I/O, with optional real-time preview via Matplotlib.

## Features

- Dynamic insertion of images following a spiral order.  
- Canvas auto-expands: 1×1 → 3×3 → 5×5 → 7×7 → …  
- Supports grayscale, RGB, and alpha-channel images.  
- Real-time visualization with Matplotlib.  
- Export final mosaic directly to PNG.

## Installation

```bash
git clone https://github.com/JosepCru/Image-Spiral-Canvas.git
cd Image-Spiral-Canvas
pip install -r requirements.txt
