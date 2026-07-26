# Repositório contendo as camadas utilizadas nas análises

## elevation
[Elevation data 30 s](Elevation) is from the SRTM elevation data. WorldClim2.1. https://www.worldclim.org/data/worldclim21.html Accessed 25 Jul 2026

## Bioclimatic variables 10 m
[19 bioclimaric variables 10 m](Bioclim%20variables%2010m). WorldClim2. https://www.worldclim.org/data/worldclim21.html Accessed 25 Jul 2026

## Bioclimatic variables 30 s
[19 bioclimaric variables 30 s](Bioclim%20variables%2030%20s). WorldClim2. https://www.worldclim.org/data/worldclim21.html Accessed 26 Jul 2026

---
## Install Git LFS (case you run git pull or git push)

Know that you need to ```git clone``` the repository before this step

In terminal
```
brew install git-lfs
git lfs install
git lfs pull
```
In case you want to push a large file, just follow the normal workflow:

```
git pull
git add .
git commit # using -m as a detailed commit message
git push origin main
```

Git LFS helps to pull and push large files (>400 Mb & <2Gb)
