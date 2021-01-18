## BACKGROUNG

Microscopic examination of suspected tissue is regarded as the gold standard for the clinical diagnosis of cancers. Normal and tumorous tissues differ for several characteristics: cell density, cell size, cell heterogeneity, vasculature integrity and tissue morphology. If the histological type is different from what is usually found in the tissue being examined, it can point to a cancerous phenotype. 
Even though diagnosis made by the doctor is the current best tool for cancer and tumor diagnosis, it is time consuming and leaves room for human error. In principle, analysis of histological images could be automated and deep learning algorithms may be able to accurately detect cancerous lesions, allowing the physician to take care of other medical matters.
The goal is this project is to build and tune up a deep learning algorithm for the detection of cancerous lesions in histological images. 

## DATA OVERVIEW AND EDA
The dataset is available on Kaggle (https://www.kaggle.com/c/histopathologic-cancer-detection) and contains 220025 color (RGB) images (96x96 pixels). Most of the images, 59.5%, are showing normal tissue. The two classes are balanced; thus, we can avoid over-sampling or under techniques that handle unbalanced data sets.

<img src="https://github.com/Gianl-msi/Histopathologic-Cancer-Detection/blob/main/Figures/distribution.JPG" width="450" height="450"/>

The image below shows an example of normal and tumor tissue. While the normal tissue appears well organized, the tumor cells are mangled up and the normal structure of the tissue is missing.

<img src="https://github.com/Gianl-msi/Histopathologic-Cancer-Detection/blob/main/Figures/image%20example.JPG" width="600" height="300"/>
