# Image Patch Extraction

This project contains a script that converts untrained images into image patches using a YOLOv4-based detection model. It also creates a log of images where no patches were found.

## Tasks Done
- Converted around 9000 untrained images into cropped patches.
- Created a log file for images with no valid bounding box detections.
- Saved patch images class-wise inside appropriate folders.
- Script tested and saved on Signdesk PC.

## Files
- `patch_extractor.py` – Main script for processing and patching.
- `no_patch_images.txt` – List of images that did not yield any patches.
- `Documents.md` – Additional details like folder structure and image count.
