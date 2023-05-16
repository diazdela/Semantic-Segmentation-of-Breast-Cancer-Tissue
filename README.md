# Semantic-Segmentation-of-Breast-Cancer-Tissue
Authors: Aidan Franklin, Ethan Cossu, Victoria Diaz de la Rocha

The main commands used were calling the GitHub repositories where we obtained the dataset and models such as
!git clone
and 
!pip install

We also had to import semantic segmentation functions such as 
from torchvision import transforms
from segmentation.data_loader.segmentation_dataset import SegmentationDataset

There was also a lot of path calling due to the amount of images and masks
ex: r'/content/CrowdsourcingDataset-Amgadetal2019/images'

As for contribution:
Aidan Franklin and Ethan Cossu: found the Breast Cancer Semantic Segmentation Dataset file
Victoria Diaz de la Rocha: found the Pytorch semantic segmentation model file
