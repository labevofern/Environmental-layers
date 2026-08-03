# Repositório contendo as camadas utilizadas nas análises

## Elevation
[Elevation data 30 s](Elevation) is from the SRTM elevation data. WorldClim2.1. https://www.worldclim.org/data/worldclim21.html Accessed 25 Jul 2026

## Bioclimatic variables 10 m
[19 bioclimaric variables 10 m](Bioclim%20variables%2010m). WorldClim2. https://www.worldclim.org/data/worldclim21.html Accessed 25 Jul 2026

## Bioclimatic variables 30 s
[19 bioclimaric variables 30 s](Bioclim%20variables%2030%20s). WorldClim2. https://www.worldclim.org/data/worldclim21.html Accessed 26 Jul 2026

## Net Primary Production (NPP) for 2000 - 2015 30s
MODIS MOD17 annual/30-arcsec [Net Primary Production (NPP)](Net%20primary%20production%2030%20s) for 2000 - 2015 in a convenient GIS-friendly GeoTIFF format. Please see http://www.ntsg.umt.edu/project/mod17 for an overview of the MOD17 
model and data product.

## Cloud variables
### Cloud forest prediction
[Cloud forest prediction 30 s](Cloud%20variables/Cloud%20forest%20prediction). EarthEnv. https://www.earthenv.org/cloud Accessed 03 Aug 2026

## Soil variables
[Soil variables](Soil%20variables). SoilGrids. https://soilgrids.org/
* [Cation exchange capacity (at ph 7)](Soil%20variables/soilgrids-isric_myRegion_cec_5-15cm_mean.tif)
* [Clay content](Soil%20variables/soilgrids-isric_myRegion_clay_5-15cm_mean.tif)
* [pH water](Soil%20variables/soilgrids-isric_myRegion_phh2o_5-15cm_mean.tif)
* [Sand](Soil%20variables/soilgrids-isric_myRegion_sand_5-15cm_mean.tif)
* [Silt](Soil%20variables/soilgrids-isric_myRegion_silt_5-15cm_mean.tif)
* [Soil organic carbon](Soil%20variables/soilgrids-isric_myRegion_soc_5-15cm_mean.tif)

---
## Install Git LFS (case you run git pull or git push)

Know that you need to ```git clone``` the repository before this step

In terminal
```
brew install git-lfs
git lfs install
git lfs pull
```
In case you want to push a large file, just follow the LFS workflow:

```
git lfs install
git lfs track "*.tif"
git add .gitattributes
git add .
git commit # using -m as a detailed commit message
git push origin main
```

Git LFS helps to pull and push large files (>100 Mb & <2Gb)
