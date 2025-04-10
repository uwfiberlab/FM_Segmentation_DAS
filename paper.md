# Phase Picking - Distributed Acoustic Sensing (DAS) Foundation Model (FM)
## Literature Review / Introduction:
**Read papers**
*DAS overview and current technology
* Current Phase picking models and slow speeds
* Goal to speed up process for this     
* state of the art

* Most if not all papers talk about the discussion of dark fiber from the early papers. More papers discussing need for lit fiber sensing * Possibly, to show connect back to reason for utilizing this infrastructure*

DAS allows for monitoring of geophysical occurances and acoustic signals propagating along the fiber-optic cable. Utilization of this monitoring allows for examination of mutliple different earth processes which include: analysis of total water content utilizing velocity variations in the near-surface (Dou et al., 2017), 

* DAS utilizes sources of seismic energy (train noise) to sample as it is a passive mode of sensing (Ajo-Franklin et al., 2019). Can generate upwards of 20 TB / day at highest resolution. 

* Papers discuss noise as a factor and could be a connection between our model and others??

* DAS can be utilized as a source of data for early warning systems due to the fine spatial resolution that it offers (Zhan, 2019). It could allow isolation of areas it appears. "10-100 meter scales" according to paper.

## Data
* for my section it will be the GCI Alaska data
* describe cable location, dates used for cable, how much data


## Methods:
* describe the pipeline for the model as well as the training utilized for the model

### Model:
* Adaptation from Qibin's model which recreates the decoder for phase picking utlization

### Phase Picking:
* Took previously phase picked data and created masks by removing outliers and reinterpolating p-wave and s-wave picks for a shallow gradient
  
### Training:
* will take masks and input into the dataset using train test split and evaluate performance using Loss curves + performance metrics.

## Results
* undergo an evaluation of how the methods were utilized and how well it was able to segment out specific waves
* Focus of phase picking for segmentation - method perspection
* Can we improve picking performance and computing time with segmentation?"

## References:
