# vessel-analyzer
Vessel Analyzer is a browser-based research tool for quantitative analysis of coronary microvasculature from angiography image sequences. It implements two complementary analysis approaches: (i) Frangi vesselness filtering (Frangi et al. 1998, Medical Image Computing) and (ii) a Pearson-based intensity analysis method  (Jenkins et al., 2012, Arterioscler Thromb Vasc Biol). The tool runs entirely in the browser using Pyodide and scikit-image. The software was developed by Vasco Sequeira and is intended for research use only; it is not designed for clinical decision-making.

## Features

- Quantitative measurement of vessel area and vessel fraction from angiography images
- Dual analysis methods: (i) Frangi vesselness filtering for structural vessel enhancement and segmentation, (ii) Pearson-based intensity analysis for complementary vessel detection and validation
- Adjustable vessel width (sigma) and minimum segment size
- ROI-based analysis with polygon drawing
- Manual paint and erase tools for correction of missed or incorrect vessel segments
- Sequence analysis for image stacks across the cardiac cycle
- Projection-based analysis: (Mean, Median, Min, Max Vesselness, Std Dev)
- Batch export of measurements and analyzed images

## Usage

Open the live GitHub Pages site, upload one or more angiography images, set the pixel size and filter parameters, and click Run to analyze the current image. Both analysis methods are available within the interface and can be used independently or in parallel for comparison. Results can be saved to the log and exported as CSV or image files.

## Notes

This tool is intended for research use only and is not designed for clinical decision-making.
