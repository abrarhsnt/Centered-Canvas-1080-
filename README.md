Image Converter & Canvas Resizer

This script converts images in a given folder to square 1080×1080 PNGs with a white background canvas. It is useful for preparing uniformly sized images for social media, presentations, or archives.

How it works

-Place all your images inside the folder you want to process.

-Set the path of that folder in the input_dir variable inside the script.

-The script will create a subfolder named output inside that directory.

-All processed images will be saved as .png files into the output folder.

-Images smaller than 1080×1080 are centered on the canvas.

-Larger images are resized proportionally to fit within the 1080×1080 canvas before being centered.

Supported formats

.jpg, .jpeg, .png, .bmp, .tiff

Usage

Install dependencies:

pip install pillow


Edit the input_dir variable in the script to point to your image folder.

Run the script:

python convert_images.py


Check the new output folder for your processed PNGs.
