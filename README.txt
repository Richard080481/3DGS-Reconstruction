South Building subsets for CSCI 677 Assignment 3 (Fall 2026)
Source: https://demuc.de/colmap/datasets/
These are resized to 1600x1200 from the original COLMAP South Building images.
images30: 30 consecutive photographs, sorted original positions 49 through 78.
images15: every other image from images30 (positions 1,3,...,29).
Number images in alphabetical filename order within each folder.
For the 30-image Gaussian Splatting evaluation, withhold images #10, #20, #30
from GS training, but include all 30 in the COLMAP reconstruction.
selection.json maps each subset position to the filename and original position.
