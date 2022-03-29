# ci-tiger-connectivity-synthesis

Central India Tiger Connectivity Synthesis Project Notes

  - Layers projected to World Mercator (EPSG 3395)
  
  - Layers resampled (bilinear interpolation) to 250m resolution
  
  - Layers masked to union shape
  
  - Yumnam et al. (2014) nightlight areas set to 1 for resistance analysis
  
  - Current analysis performed in Circuitscape 4.0 standalone GUI  
  
  - Current Analysis Notes:
    	- Resistance rasters with raw values (after alignment and 250m projection)
    	- PA layer used as nodes (details in paper/supplementary information)
    	- Pairwise modeling mode
    	- Cumulative pairwise curent flow option selected
    	- Nodes left hot (not set to 0)
