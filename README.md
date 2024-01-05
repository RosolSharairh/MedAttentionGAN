# MedAttentionGAN: 
## Summary

This code is part of the Deep Learning Course instructed by Dr. Tamam Alsarhan at the University of Jordan.


## Setup
To run the [`code.ipynb`](code.ipynb) file with no problems, make sure that your configuration is as follows:
* Python version: `3.8.17`.
* CUDA version: `11.7`.
* GPU: NVIDIA V100.
* Dependencies are available in [`requirements.txt`](requirements.txt), run `pip install -r requirements.txt`.


## Models
[This is a Jupyter notebook that contains the models.](link.ipynb)
## Datasets & Preprocessing
We used paired and unpaired MR/CT images from different sources. For the preprocessing we resized all images to be (256,256) and unified the format to png.
1. Paired CT/MR Dataset:
- [The Magnetic Resonance - Computed Tomogra-
phy (MR-CT) Jordan University Hospital (JUH)]
 2. Unpaired datasets:
 - [Brain CT images with intracranial hemorrhage masks](https://www.kaggle.com/datasets/vbookshelf/computed-tomography-ct-images/data)
 - [CT of the brain](https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain)
 - [Brain tumor MRI dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data)
 - [Radiological Society of North America (RSNA) for Intracranial Hemorrhage Detection](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/overview)
 - [Brain tumor MRI dataset](https://www.kaggle.com/datasets/ahmedhamada0/brain-tumor-detection)
 
## Pretrained Weights
Pretrained Weights could be found in this [`Google Drive link`](link).

## Contact Us
If you encounter any issues and need assistance, please sumbit an issue on this GitHub repository, or contact us via [abdelrahman.sabbagh@kaust.edu.sa](mailto:abdelrahman.sabbagh@kaust.edu.sa). Thank you for your interest in reproducing the results!
