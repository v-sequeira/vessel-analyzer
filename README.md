# vessel-analyzer

Browser-based tool for quantitative analysis of coronary microvasculature from angiography image sequences

Vessel Analyzer is a browser-based research tool for quantitative analysis of coronary microvasculature from angiography image sequences. It applies a Frangi vesselness filter (Frangi et al. 1998, *Medical Image Computing*) and runs entirely in the browser using Pyodide and scikit-image. The software was developed by Vasco Sequeira, for research use only and is not intended for clinical decision-making.

## Features

- Quantitative measurement of vessel area and vessel fraction from angiography images
- Frangi vesselness filtering for vessel enhancement and segmentation
- Adjustable vessel width (sigma) and minimum segment size
- ROI-based analysis with polygon drawing
- Manual paint and erase tools for correction of missed or incorrect vessel segments
- Sequence analysis for image stacks across the cardiac cycle
- Projection-based analysis (Mean, Median, Min, Max Vesselness, Std Dev)
- Batch export of measurements and analyzed images

## Usage

Open the live GitHub Pages site, upload one or more angiography images, set the pixel size and filter parameters, and click **Run** to analyze the current image. Results can be saved to the log and exported as CSV or image files.

## Notes

This tool is intended for research use only and is not designed for clinical decision-making.
