# Airport-Baggage-Scanning-and-threat-detection-using-ML
Baggage Screening Scanner for dangerous objects
ML is leveraged to train algorithms using X-Ray data for baggage screening. These algorithms can then autonomously identify actual threats with very high probability, minimizing the risk of human error and ensuring a consistent level of security.
Airports & railway stations around the world, mostly check luggage contents manually. This is done by viewing X-ray images of the bag which reveal its contents. This project aims at automating this exact process , using deep learning based object detectors.
### BagGAN - Synthetic Baggage Scan Generation with StyleGAN2-ADA
gan.tar.gz) and copy them in `checkpoints/` directory.

### Usage
To train the BagGAN model from a scratch, the user can run the following code:
A Python library for StyleGAN-based generation of synthetic baggage X-ray images for prohibited item detection.

The package consists of a [StyleGAN2-ADA](https://github.com/NVlabs/stylegan2-ada-pytorch) model designed to simulate baggage X-ray/CT scans for airport security screening. The training and testing scripts in the open-source package are used to train the model on the [PIDRay](https://arxiv.org/abs/2211.10763) benchmark which can be downloaded from this [link](https://github.com/bywang2018/security-dataset). The dataset consists of ~47,000 samples of baggage scans packed with 14 different prohibited items for airport security inspection. 

![](figures/test_samples.png)

The model has been used to create a framework for generating annotated baggage X-ray scans for security inspection. The framework has been described in our paper: [Self-Supervised One-Shot Learning for Automatic Segmentation of StyleGAN Images
