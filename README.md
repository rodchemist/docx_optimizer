# DocX Image Optimizer

A cross-platform GUI utility to optimize images in `.docx` files and back up originals. It preserves folder structures, supports adjustable compression settings, and displays a summary of size savings.

## Features
- Select origin and destination directories.
- Back up original files to `<destination>/backup/`.
- Optimize images in `.docx` files and save to `<destination>/optimized_files/`.
- Adjust compression settings (max dimension, JPEG quality, WebP quality) via GUI.
- Cross-platform (Windows, Linux, macOS).
- Modern GUI with theme support.
- Thread-safe processing with progress updates.
- Robust error handling and logging.

## Requirements
- Python 3.6+
- Required Python packages (listed in `requirements.txt`):
  - Pillow
  - ttkthemes
  - imageio

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/docx-optimizer.git
   cd docx-optimizer
