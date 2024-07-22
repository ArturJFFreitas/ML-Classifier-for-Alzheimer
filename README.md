By Artur Freitas & Rita Barnabé, arturfreitas09@gmail.com & rita.barnabe@ua.pt 01/05/2023

This Python script performs a binary classification using three methods
* Support Vector Machine
* Random Forest
* Neural Networks

That classification was performed for three instances:
* Control vs Alzheimer
* Control vs Mild Cognitive Impairment (MCI)
* MCI vs Alzheimer

The whole process includes:
* Data preparation
* Feature selection
* Training and validation approaches
* Performance evaluation
* Feature ranking

The database used is composed of radiomics features image analysis of left hippocampus ROIS after subcortical segmentation of neuro MR studies from a ADNI repository (https://adni.loni.usc.edu/), and the image segmention was performed by the VolBrain (https://www.volbrain.upv.es/) online brain volumetry platform. The radiomicsfeatures were computed by the LifeX (https://www.lifexsoft.org/) software tool. 
