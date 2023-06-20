# SoilMoisture
Attempt to differentiate soil moisture from conventional camera images

Example1 uses image intensity of CIELUV (https://en.wikipedia.org/wiki/CIELUV) to calculate the intensity of images. Wet soil/ground absorbs more light, resulting in a positive skew in pixel intensity histogram. Skewness is calculated for dry vs. wet riverbed region for an example.
