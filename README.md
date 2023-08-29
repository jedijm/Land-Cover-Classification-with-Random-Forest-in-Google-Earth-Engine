# Land Cover Classification with Machine Learning Algorithm (Random Forest) in Google Earth Engine

## Project Background
Data Used:
**Sentinel-2 MSI: MultiSpectral Instrument, Level-2A**

Tools:
**Google Earth Engine**

Area of Interest (AOI):
**Palembang**

Bands Used:
`B2`, `B3`, `B4`, `B8`
Additional Bands: `NDVI` & `SR`.

## Import Sentinel-2 Data
<p align="center">
  <img src= "https://github.com/jedijm/Land-Cover-Classification-with-Random-Forest-in-Google-Earth-Engine/blob/main/asset/sentinel.png"> <br>
Fig 1. Sentinel-2 with Natural Color Band Combination
</p>

## Select Samples and Classify into 4 Land Covers:
1. Water
2. Vegetation
3. Building
4. Open Land

## Build Random Forest Model
<p align="center">
  <img src= "https://github.com/jedijm/Land-Cover-Classification-with-Random-Forest-in-Google-Earth-Engine/blob/main/asset/Model.png"> <br>
Fig 2. Random Forest Model
</p>
Train the model with training data to see the accuracy.

The accuracy for the model is **0.9592467043314501** , thus it is rather good to continue with test data.

## Classification Result
<p align="center">
  <img src= "https://github.com/jedijm/Land-Cover-Classification-with-Random-Forest-in-Google-Earth-Engine/blob/main/asset/classification.png"> <br>
Fig 3. Land Cover Classification
</p>
