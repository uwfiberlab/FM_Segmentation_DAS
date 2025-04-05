# FM_Segmentation_DAS
Repository dedicated to the creation of a segmentation subsection for a Distributed Acoustic Sensing (DAS) machine learning foundation model.

## What is DAS:
Distributed Acoustic Sensing (DAS) is a geophysical tool that utilizes fiber-optic cables as a way of geophysical monitoring. It transforms the fiber-optic cable into an array of single-component seismometers at a given spaced interval. A major hurdle when utilizing DAS data is large output size of every file of raw data, which makes data analysis difficult.

Data processing in geophysics has multiple tasks. The most basic ones are denoising, event detection and discrimination, and seismic phase picking: some of these are regressions, some of these are classification. Given the multiple tasks and massive data volume, there is an opportunity to build a general feature extraction model framed as a “foundation model”.

This repository is used for a new earthquake phase picking deep learning model for DAS trained on Cook Inlet - Alaska DAS data.

## Steps to Set Up the Environment

### 1. Clone the Repository

To clone the repository to your local machine, use the following command:

```
git clone https://github.com/uwfiberlab/FM_Segmentation_DAS.git
```

### 2. Navigate to the Repository 

Navigate to GitHub file locations: 
```
cd ..
```

Navigate to repository:
```
cd filepath/path
```

### 3. Create the environment

To create the virtual environment to use with any Foundation Model DAS packages, use the following command while in the repository:
```
conda env create -f env.yml
```
### 4. Activate the environment
```
conda activate FM_DAS
```

## Adapted From / Original Model Reference:
Shi, Q., Denolle, M. A., Ni, Y., Williams, E. F., & You, N. (2025). Denoising Offshore Distributed Acoustic Sensing Using Masked Auto-Encoders to Enhance Earthquake Detection. Journal of Geophysical Research: Solid Earth, 130(2), e2024JB029728. https://doi.org/10.1029/2024JB029728
