# Image Analysis
Collection of useful scripts and python code for mask generation, data extraction and plotting etc.

**Cell Mask Generator:** ImageJ macro that takes a highly multiplexed tiff image (such as that generated by Imaging mass cytometry), and walks you through generating a multichannel .tif file where each channel contains a binary image of a single cell. This can be used for masking in automated data extraction on a per-egg basis.


**MCD to TIFF:** Jupyter notebook that uses the Bodenmiller lab's IMCtools python package to generate tiff files from a .zip file containg a .mcd file. 
