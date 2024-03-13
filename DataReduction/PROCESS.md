Given: raw data

The following has been done on the raw images:
- RemoveBad was ran to remove shaky images
- Upon running StackFits, it was revealed that the images need to be aligned, thus, the new script RealignFits will be run.
- RealignFits successfully realigned the images and allowed StackFits to stack the images to the subfolder /stacked
- The next file will be KingFit, which will perform aperture photometry to get the King Fitting parameters