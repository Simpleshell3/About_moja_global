# Moja Global Land Sector Data Analysis Guide

## 1.0 Introduction

This document aims to guide contributors to report the analysis of 

[Moja Global's Land Sector Dataset](https://datasets.mojaglobal.workers.dev/0:/).<br> 

---

### 1.0.0 The Land Sector Dataset
The dataset is a collection of publicly available [Open source datasets](https://github.com/moja-global/Land_Sector_Datasets), which you can choose any and work on. 

- Many countries/regions use this dataset and it works well in real global scenarios. For each data set, information about content and licenses is provided. Appropriate permissions are cited for all datasets, and we urge you to follow the license before continuing to use each dataset.

If you have another dataset on your mind that would be beneficial to [Moja Global's mission](https://moja.global/), feel free to reach out to us at [info@moja.global](info@moja.global) to share details about this dataset.

---

### 1.0.1 Data Analysis Software and Notebooks

Notebooks are documents produced by the data analysis software, which contain both computer code (e.g. python) and rich text elements (paragraph, equations, figures, links, etc…). 
>Notebook documents are both human-readable documents containing the analysis description and executable code which can be run to perform data analysis. 

Select software that supports geospatial analysis. 
- Moja Global is an open-source project, and the interest here is to share your process (code) and results (explanation) to support the open-source movement. To effectively record your analysis, we recommend that you use a [notebook](https://sourceforge.net/software/product/Google-Colab/alternatives). 

---

### 1.0.2 Contributing

When your contribution is ready; raise a PR to have it merged. Refer to the [community website](https://community.moja.global/community/code-contribution) to know how to make a pull request.

>If you have experience and want to help, send an email to [mentorship@moja.global](mailto:mentorship@moja.global). We are open to mentoring new developers and contributors through various mentorship programs and initiatives.

---

### 1.0.3 The Analysis

When we look at climate action, we would like to get descriptions from a global scale to a specific state administration within a particular country. A draft review of the characteristics of each file in the dataset is found [here](https://github.com/Simpleshell3/Land-Sector-Dataset-Description/blob/main/Land-Sector-Dataset-Description.md).

Amongst the numerous factors that affect climate change, the Agriculture, Forestry, and Other Land Use (AFOLU) sector is responsible for almost a quarter of the global Greenhouse gases (GHG) emissions. The emissions associated with AFOLU activities are projected to increase in the future.


The following sections guide you on how to document your analysis at any scale (global, continental, country, state).


[**1.1 Global Analysis**](/Contributing/How-to-Contribute-Land-Sector-Data-Analysis.md#11-global-analysis)

[**1.2 Continental Analysis**](/Contributing/How-to-Contribute-Land-Sector-Data-Analysis.md#12-continental-analysis)

[**1.3 Country Analysis**](/Contributing/How-to-Contribute-Land-Sector-Data-Analysis.md#13-Country-analysis)

[**1.4 State/Province/County/Region/City Analysis**](/Contributing/How-to-Contribute-Land-Sector-Data-Analysis.md#14--stateprovincecountyregioncity-analysis)

---

## 1.1 Global Analysis

This is the study of the Globe's features, activities, and consequences on climate change. Some factors that should guide your analysis include the following. 

---

### 1.1.0  The Globe's Boundary

In the first section of your global analysis notebook, it is suitable to:

1. State the aim of the analysis. 
2. Define the [boundary](https://datasets.mojaglobal.workers.dev/0:/Administrative/Boundaries/) of the Globe with a figure and brief topological description
3. Present a figure with the Globe's [protected areas](https://datasets.mojaglobal.workers.dev/0:/Administrative/Protected%20Areas/) and describe how it has affected global changes.
4. Present a figure showing the complex road network of the Globe
5. Provide a summary of how the Globe's  celestial location results in climate change.

---

### 1.1.1 The Globe's BioClimatic Zones<br>

Explore the Globe's 
[bioclimatic zone dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/). 
Fill in this section by trying to answer the following questions:

1. What are the hot zones of the Globe? (provide a figure with the biodiversity hotspots)
2. Which continents/countries/states are dominant/repressive with hotspots?
3. What life is characteristic of the hotspots?
4. What life is going extinct on Globe with the given data?

The files contain more features that should be exploited.

---

### 1.1.2 The Globe's AgroEcological Zones

Explore the AgroEcological climate of the Globe and reveal information about the following:

1. The agro hotspots
2. Dominant soil and related features
3. Restricted areas from cultivation
4. Nutrient availability
5. Water scarcity.
6. Types of protected Areas

The files contain more features to be exploited

---

### 1.1.3 The Globe's Ecological Zones

Explore the ecological zone [dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/Global_Ecological_Zone_GEZ/). Displaying it reveals interesting patterns.

---

### 1.1.4 The Globe's Climate

Explore the Globe's climate [dataset](https://datasets.mojaglobal.workers.dev/0:/Climate/) from KoppenGeiger and IPCC. It would be suitable to give brief figurative descriptions of the climate shifts.

---

### 1.1.5 The Globe's Landcover

The Landcover dataset contains interesting information on Biomass carbon,
Forest, Forests loss, and Land use.

Explore this dataset to find relationships between any activities such as cropland and forest loss etc. 

---

### 1.1.6 The Globe's Soil Resources

Soil composition is an important factor that affects settlement and human activities. Display the data, identify relationships between attributes such as locations and crop production, nutrient availability and intensive agriculture etc


---

### 1.1.7 Interpretation of Results

This is the most important part of the analysis. The whole process comes down to this very aspect of drawing insight from the data. Being able to explain complex relationships that exist between **1.1.1** and **1.1.6**. 

In this section, you can statistically elaborate on how the individual features of each factor above affect climate change. Present your opinion scientifically and use your calculations, references, and description to back up your facts.

---

### 1.1.8 Recommendation and Conclusion

Use this section as an opportunity to present possible recommendations on how managing the evaluated factors would benefit the globe and help control, mitigate, and adapt to climate changes.

---

## 1.2 Continental Analysis

If you are interested in analyzing a given continent, then this is the right guide for you. The dataset available in the repository can be manipulated(joined, merged, concatenated, etc) to narrow down to any continent.

Moreover, some files can be queried to display information only for a defined area. Use the following characteristics as a guide to analyzing a continent.

---
### 1.2.0  The Continent's Boundary

In the first section of your continental analysis notebook, it is suitable to:


1. State the aim of the analysis. 
2. Define the [boundary](https://datasets.mojaglobal.workers.dev/0:/Administrative/Boundaries/) of the continent with a figure and brief topological description
3. Present a figure with the continent's [protected areas](https://datasets.mojaglobal.workers.dev/0:/Administrative/Protected%20Areas/) and describe how it has affected a continental shift in climate and activities.
4. Present a figure showing the complex road network of the continent.
5. Provide a summary of how the continent's geographical location results in climate shifts within the area.

---

### 1.2.1 The Continent's BioClimatic Zones

Explore the continent's [bioclimatic zone dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/). If the dataset contains other continental information, filter out the continents you are not analyzing.
Fill in this section by trying to answer the following questions:

1. What are the hot zones of the continent? (provide a figure with the biodiversity hotspots)
2. Which countries/states are dominant/repressive with hotspots?
3. What life is characteristic of the hotspots?
4. What life is going extinct on the continent with the given data?
5. What is the population of the continent?

The files contain more features that should be exploited. Identify more characteristics that you find interesting

---

### 1.2.2 The Continent's AgroEcological Zones

Explore the AgroEcological climate of the continent and reveal information about the following:

1. The agro hotspots of the continent
2. Dominant soil and related features within the continent
3. Restricted areas from cultivation
4. Nutrient availability
5. Water scarcity.
6. Types of protected Areas

The files contain more features to be exploited

---

### 1.2.3 The Continent's Ecological Zones

Explore the ecological zone [dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/Global_Ecological_Zone_GEZ/). Displaying it reveals interesting patterns.

---

### 1.2.4 The Continent's Climate

Explore the continent's climate [dataset](https://datasets.mojaglobal.workers.dev/0:/Climate/) from KoppenGeiger and IPCC. It would be suitable to give brief figurative descriptions of the climate shifts of the continent. What are the key characteristics of the climate and how does it vary over place and time

---

### 1.2.5 The Continent's Land Cover

The land cover dataset contains interesting information about biomass carbon, forests, forest loss, and land use.

Explore this data set to find the relationship between any activities (such as cultivated land and forest loss, etc.). 
In the case where you can't find complete one-file datasets, try merging or filtering some of the datasets to get the data of interest.

---

### 1.2.6 The Continent's Soil Resources

Soil composition is an important factor that affects settlement and human activities. Display the data, identify relationships between attributes such as locations and crop production, nutrient availability and intensive agriculture etc


---

### 1.2.7 Interpretation of Results

This is the most important part of the analysis. The whole process comes down to this very aspect of drawing insight from the data. Being able to explain complex relationships that exist between **1.2.1** and **1.2.6**. 

In this section, you can statistically elaborate on how the individual features of each factor above affect climate change. Present your opinion scientifically and use your calculations, references, and description to back up your facts.

---

### 1.2.8 Recommendation and Conclusion

Use this section as an opportunity to present possible recommendations on how managing the evaluated factors would benefit the people and help control, mitigate and adapt to climate changes.

---

## 1.3 Country Analysis

If you are interested in analyzing a given country, then this is the right guide for you. The dataset available in the repository can be manipulated(joined, merged, concatenated, etc) to narrow down to any continent.

Moreover, some files can be queried to display information only for a defined area. Use the following characteristics as a guide to analyzing a given country.

---

### 1.3.0  The Country's Boundary

In the first section of your Country analysis notebook, it is suitable to:

1. State the aim of the analysis. 
2. Define the [boundary](https://datasets.mojaglobal.workers.dev/0:/Administrative/Boundaries/) of the country with a figure and brief topological description
3. Present a figure with the country's [protected areas](https://datasets.mojaglobal.workers.dev/0:/Administrative/Protected%20Areas/) and describe how it has affected the climate shift in climate and activities.
4. Present a figure showing the complex road network of the country.
5. Provide a summary of how the country's geographical location results in climate shifts within the area.

---

### 1.3.1 The Country's BioClimatic Zones

Explore the country's [bioclimatic zone dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/). If the dataset contains other Country information, filter out the countries you are not analyzing.
Fill in this section by trying to answer the following questions:

1. What are the hot zones of the country? (provide a figure with the biodiversity hotspots)
2. Which states are dominant/repressive with hotspots?
3. What life is characteristic of the hotspots?
4. What life is going extinct in the countries with the given data?
5. What is the population of the country?

The files contain more features that should be exploited. Identify more characteristics that you find interesting.

---

### 1.3.2 The Country's AgroEcological Zones

Explore the AgroEcological climate of the country and reveal information about the following:

1. The agro hotspots of the country
2. Dominant soil and related features within the country
3. Restricted areas from cultivation
4. Nutrient availability
5. Water scarcity.
6. Types of protected Areas

The files contain more features to be exploited

---

### 1.3.3 The Country's Ecological Zones

Explore the ecological zone [dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/Global_Ecological_Zone_GEZ/). Displaying it reveals interesting patterns.

---

### 1.3.4 The Country's Climate

Explore the country's climate [dataset](https://datasets.mojaglobal.workers.dev/0:/Climate/) from KoppenGeiger and IPCC. It would be suitable to give brief figurative descriptions of the climate shifts of the country. What are the key characteristics of the climate and how does it vary over place and time

---

### 1.3.5 The Country's Landcover

The Landcover dataset contains interesting information on Biomass carbon,
Forest, Forests loss, and Land use.

Explore this dataset to find relationships between any activities such as cropland and forest loss etc. 
In the case where you can't find complete one-file datasets, try merging or filtering some the of datasets to get the data of interest.

---

### 1.3.6 The Country's Soil Resources

Soil composition is an important factor that affects settlement and human activities. Display the data, identify relationships between attributes such as locations and crop production. nutrient availability and intensive agriculture, etc

---

### 1.3.7 Interpretation of Results

This is the most important part of the analysis. The whole process comes down to this very aspect of drawing insight from the data. IScaniScan explains the complex relationship between **1.3.1** and **1.3.6**.

In this section, you can statistically explain in detail how the various characteristics of each of the above factors affect climate change. Present your opinion scientifically and use your calculations, references, and descriptions to back up your facts.

---

### 1.3.8 Recommendation and Conclusion

Use this section as an opportunity to present possible recommendations on how managing the evaluated factors would benefit the people and help control, mitigate and adapt to climate changes.

---

## 1.4  State/Province/County/Region/City Analysis

If you are interested in analyzing remote geographic areas (such as cities, states, or provinces), then this is the guide for you. The data sets available in the repository (join, merge, join, etc.) can be manipulated to narrow down to any continent.

---

### 1.4.0  The State's Boundary

In the first section of your state's analysis notebook, it is suitable to:

1. State the aim of the analysis. 
2. Define the [boundary](https://datasets.mojaglobal.workers.dev/0:/Administrative/Boundaries/) of the state with a figure and brief topological description
3. Present a figure with the state's [protected areas](https://datasets.mojaglobal.workers.dev/0:/Administrative/Protected%20Areas/) and describe how it has affected the climate shift in climate and activities.
4. Present a figure showing the road network of the state.
5. Provide a summary of how the state's geographical location results in climate shifts within the area.

---

### 1.4.1 The State's BioClimatic Zones

Explore the state's [bioclimatic zone dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/). If the dataset contains other Country information, filter out the regions you are not analyzing.


Fill in this section by trying to answer the following questions:


1. What are the hot zones of the state? (provide a figure with the biodiversity hotspots)
2. Which areas are dominant/repressive with hotspots?
3. What life is characteristic of the hotspots?
4. What life is going extinct in the state with the given data?
5. What is the population of the state?

The files contain more features that should be exploited. Identify more characteristics that you find interesting

---

### 1.4.2 The State's AgroEcological Zones

Explore the AgroEcological climate of the state and reveal information about the following:

1. The agro hotspots of the state
2. Dominant soil and related features within the state
3. Restricted areas from cultivation
4. Nutrient availability
5. Water scarcity.
6. Types of protected Areas

The files contain more features to be exploited

---

### 1.4.3 The State's Ecological Zones

Explore the ecological zone [dataset](https://datasets.mojaglobal.workers.dev/0:/Bioclimatic&EcologicalZones/Global_Ecological_Zone_GEZ/). Displaying it reveals interesting patterns.

---

### 1.4.4 The State's Climate

Explore the state's climate [dataset](https://datasets.mojaglobal.workers.dev/0:/Climate/) from KoppenGeiger and IPCC. It would be suitable to give brief figurative descriptions of the climate shifts of the state. What are the key characteristics of the climate and how does it vary over place and time?

---

### 1.4.5 The State's Landcover

The Landcover dataset contains interesting information on Biomass carbon,
Forest, Forests loss, and Land use.

Explore this dataset to find relationships between any activities such as cropland and forest loss etc. 
In the case where you can't find complete one-file datasets, try merging or filtering some of the datasets to get the data of interest.

---

### 1.4.6 The State's Soil Resources

Soil composition is an important factor that affects settlement and human activities. Display the data, identify relationships between attributes such as locations and crop production. nutrient availability and intensive agriculture etc

---

### 1.4.7 Interpretation of Results

This is the most important part of the analysis. The whole process comes down to this very aspect of drawing insight from the data. Being able to explain complex relationships that exist between **1.4.1** and **1.4.6**. 

In this section, you can statistically elaborate on how the individual features of each factor above affect climate change. Present your opinion scientifically and use your calculations, references, and descriptions to back up your facts.

---

### 1.4.8 Recommendation and Conclusion

Use this section as an opportunity to present possible recommendations on how managing the evaluated factors would benefit the people and help control, mitigate and adapt to climate changes.

---
