# Manga Stitcher

Manga Stitcher is a straightforward tool designed to automatically combine manga pages vertically, creating a seamless reading experience. Many manga releases include extra "tail" images—often containing the scanlator's logo or credits—in separate files. This script detects and merges these pages, saving you time and ensuring your manga is presented as intended.

## Features

- Supports input from directories full of CBZ/CBR files.
- Outputs stitched images in the same format.
- Optionally recursive directory traversal.
- Configurable title and series metadata
- Safety checks for width and height mismatches. (skips)

## Requirements

- Python 3.10+
- Pip
  - Pillow
  - tqdm
  - rarfile
  - zipfile
  - cbz

## Usage

1. Clone the repository:

   ```bash
   git clone

   cd manga-stitcher
   ```

2. Run the script:

   ```bash
   python3 ./manga-stitcher.py --help
   ```

## Development

1. Create a virtual environment, or use the included Dev Container if using VSCode or DevPod.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script with your desired options.

## About

By Adil Atalay Hamamcıoğlu - [recoskyler](https://github.com/recoskyler) - 2025
