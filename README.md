**Ensemble Approach for Alzheimer's Disease Detection**


This repository contains the implementation of the paper "An Efficient Ensemble Approach for Alzheimer's Disease Detection Using an Adaptive Synthetic Technique and Deep Learning" (Diagnosis 2023, 13(15), 2489; https://doi.org/10.3390/diagnostics13152489).

**Dataset**
The project uses the Alzheimer's Dataset (4 classes of images) available on Kaggle:

https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images

**Dataset**


This dataset contains MRI images categorized into four classes:


Mild Demented

Moderate Demented

Non Demented

Very Mild Demented

**Files Description**

**individual-models.ipynb:** Jupyter notebook containing the implementation and training of individual EfficientNet-B2 and VGG16 models, including the application of ADASYN for data balancing.

**ensemble-based experiments.ipynb**: Jupyter notebook with the implementation of the ensemble model, combining EfficientNet-B2 and VGG16 using a feature concatenation process.
