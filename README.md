# Applying Explainability Techniques to Alzheimer's MRI Classification Models

This repository contains a PyTorch implementation utilizing an inflated 3D ResNet-18 architecture paired with Grad-CAM (Gradient-weighted Class Activation Mapping) to classify Alzheimer's Disease from structural 3D MRI scans while auditing the model's decision-making process.

## Final Paper
The complete research paper detailing our methodology, architecture, and findings on shortcut learning can be read in [Applying_Explainability_to_Alzheimers_MRI_Models.pdf](./Applying_Explainability_to_Alzheimers_MRI_Models.pdf).

## Dataset
This project utilizes neuroimaging data from the **Open Academic South Side Imaging Study (OASIS-3)**. Due to data privacy agreements and size constraints, the raw dataset is not included in this repository. 
* Access to the raw data can be requested directly via the [OASIS Brains Official Portal](https://www.oasis-brains.org/).

## Key Features & Pipeline
* **Data Processing:** Seamless pipeline using `nibabel` to handle downsampling and intensity normalization for 3D T1-weighted structural scans.
* **Architecture:** Inflated 3D ResNet-18 model tailored for volumetric data.
* **Explainability:** Grad-CAM layer hooks implemented to visualize class activation heatmaps across 3D brain volumes.

## Contributors
* **Korinne Ciechon** 
* **Justin Parrondo** 
