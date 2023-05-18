# SeasFire: Earth System Deep Learning for Seasonal Fire Forecasting in Europe

The ESA-funded [SeasFire project](https://seasfire.hua.gr) is exploring the potential of spatio-temporal asynchronous links happening between pre-occurring and non-overlapping atmospheric conditions and European fire regimes to predict the seasonal burned areas sizes in Europe by leveraging two major advancements of our time:
 
* the availability of a huge amount of satellite data with a good spatio-temporal resolution, which will be used as fire drivers called the Earth system variables, and 
* the progress in Deep Learning (DL) and especially in graph and image based modelling frameworks, finding methods capable of capturing the spatio-temporal interactions of the Earth System variables. 

![](/static/SeasFire_summary_slide_v1.0.png)
Summarizing slide of the SeasFire project

## SeasFire Cube: A Global Dataset for (Sub)Seasonal Fire Modeling in the Earth System

The [SeasFire Cube](https://doi.org/10.5281/zenodo.6834584) is a scientific datacube for seasonal fire forecasting around the globe. 
Apart from seasonal fire forecasting, which is the aim of the datacube can be used for several other tasks. 
For example, it can be used to model teleconnections and memory effects in the earth system. 
Additionally, it can be used to model emissions from wildfires and the evolution of wildfire regimes.

![](/static/rotating_spheres.gif)
Visualization of variables from the SeasFire Cube.

### Tutorials (Python and Julia)

NOTE: Instructions to access the dataset from Google Colab

> [Drive link to the seasfire dataset (0.25 deg)](https://drive.google.com/drive/folders/1IhpWRJXGOMJbtUctfnImuj7kCixpYBfC?usp=share_link)
>
> [Drive Link to the seasfire dataset (1 deg)](https://drive.google.com/drive/folders/1-yqhxp98YrCeg78vEeSM58r3EXO5BWwf?usp=share_link)
>
>After accessing the dataset link, you can add a shortcut to your personal google drive.
>
> Then you can open it in colab, like in [this notebook](https://colab.research.google.com/drive/1jK2vtKAnu4vurEaP7qeYhjroN2ccUV8b?usp=sharing)

The following tutorials show how to access and explore the SeasFire cube:

#### Python:
* [Zenodo Access & Basic analytics](https://github.com/SeasFire/seasfire-datacube/blob/main/Python-Tutorials/Seasfire_datacube_tutorial.ipynb)
* [Resample Data to Specific Spatio-Temporal Resolutions](https://github.com/SeasFire/seasfire-datacube/blob/main/Python-Tutorials/Resampling_spatio_temporaly.ipynb).

#### Julia:

* [Analytics with Julia](https://github.com/SeasFire/seasfire-datacube/blob/main/Julia-Tutorial/tutorial.ipynb)

## Models

Models and code will be made public as soon as our studies are further evaluated, peer-reviewed and published. Stay tuned!

## Papers and Talks

[Deep Learning for Global Wildfire Forecasting ](https://www.climatechange.ai/papers/neurips2022/52) (Neurips 2022, CCAI Workshop, Virtual)

[Earth System Deep Learning for Global Wildfire Forecasting](https://events.ecmwf.int/event/304/contributions/3734/attachments/2116/3757/ECMWF-ESA-WS_Papoutsis_Prapas.pdf) (ML4ESOP 2022, ESA-ECMWF Workshop, Reading, UK)

[Earth System Deep Learning towards a Global Digital Twin of Wildfires](https://meetingorganizer.copernicus.org/EGU23/EGU23-5443.html) (EGU 2023 -  Digital Twins of the Earth, Vienna, Austria)

## Prototype

A [first-of-its-kind prototype system](http://vmi903477.contaboserver.net/seasfire/ui) based on Deep Learning, has been deployed to predict sub-seasonal burned areas for Europe, using different environmental variables.

![](/static/seasfire_logo.png)
