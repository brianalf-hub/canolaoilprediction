# canolaoilprediction
Spatial predictive modeling for canola oil yield


## The effect of bio-climatic factors on global yield of canola oil

<p align="center">
  <img width="900" height="350" src="https://user-images.githubusercontent.com/70289096/92419145-d3a4cc00-f128-11ea-8b87-123ca34633fe.png">

<p align="center">
  <img width="900" height="350" src="https://user-images.githubusercontent.com/70289096/92418927-8542fd80-f127-11ea-93ba-8a721ed64524.png">

<p align="center">
  <img width="900" height="350" src="https://user-images.githubusercontent.com/70289096/92419039-3ea1d300-f128-11ea-8a19-d9709feef8de.png">

</p>

### Background. Agricultural crop yields are projected to become insufficient in the face of increasing world population and rapid global changes that include environmental and climatic factors. To determine how rapidly changing climate variation will affect canola oil yields, I used georeferenced USDA seed accession data to calculate regional averages of oil yields and climate data from WorldClim (https://www.worldclim.org/data/worldclim21.html). I then used the GIS capabilities of R to 1) perform a spatially-filtered model selection of climatic variables via a maximum likelihood ratio approach, and to 2) perform Bayesian spatial modeling to create a GIS map prediction of global oil yields. 

### Results. We found that mean annual temperatures and temperatures at wettest quarter strongly affect canola yield in similar patterns when all species are pooled, but when all temperature variables are projected to a predictive map (annual temperature, temperature seasonality, and temperatures at the wettest quarter), the hot spots of oil abundance (flame yellow in the figure above) coincided to regions with contrasting climates. We further identified sources of these patterns by running the same analyses in separate species (not shown). For example, carinata is a warm-climate crop, and consequently its yield is higher in regions such as Africa and warmer parts of Asia. After building temperature-yield models for each species, I will use the predicted database from these spatial models to train regression models and use machine learning to predict how canola oil yield will respond to different future climate change scenarios. 

### Importance of study. Canola oil is an important food ingredient, and can also be used as a biofuel. By expanding this model, I can determine which climatic factors affect yield for each *Brassica* oil crop. The resulting predictive model can provide a guide that shows which regions in the world these canola species can grow and produce oil abundantly, so growers both small- and industrial-scale can plan their crops accordingly. 
