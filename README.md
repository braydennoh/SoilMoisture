# SoilMoisture

## Summary
SoilMoisture is an attempt to differentiate soil moisture from conventional camera images.

[Example1](https://github.com/snohatech/SoilMoisture/blob/main/Example1.ipynb) uses image intensity of CIELUV color space (https://en.wikipedia.org/wiki/CIELUV) to calculate the intensity of images. CIELUV has an associated 2D chromaticity chart which is useful for showing additive colour mixtures. Wet soil/ground absorbs more light and show more dark pixels per area, resulting in a positive skew in pixel intensity histogram. Skewness is calculated for dry vs. wet riverbed region for an example.

## Requirements

- numpy
- matplotlib
- cv2
- os
- glob
- scikit-stats
- jupyter
