# Flood Risk Buffers

This project identifies areas within 30, 60, and 100 meters of watercourses as a proxy for flood exposure.  
The method uses open watercourse data clipped to an Area of Interest (AOI) and creates dissolved buffers for each distance band.

## Project structure
- data/raw: original data (not committed if >100MB)
- data/processed: outputs ready for sharing
- figs: exported maps for README
- maps: ArcGIS Pro or QGIS project files
- src: code/scripts
