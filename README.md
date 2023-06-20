# SoilMoisture
Attempt to differentiate soil moisture from conventional camera images

Example1 uses image intensity of CIELUV color space (https://en.wikipedia.org/wiki/CIELUV) to calculate the intensity of images. CIELUV use Cartesian-type coordinate system which is more useful in numerical and predictive analysis. CIELUV has an associated twodimensional chromaticity chart which is useful for showing additive colour mixtures. Wet soil/ground absorbs more light, resulting in a positive skew in pixel intensity histogram. Skewness is calculated for dry vs. wet riverbed region for an example.

## Requirements

- numpy
- matplotlib
- cv2
- os
- glob
- scikit-stats
- jupyter
