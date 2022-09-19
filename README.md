# A Hybrid Privacy-Preserving Deep Learning Approach for Object Classification in Very High-Resolution Satellite Images
This repository contains the code for the following publication "A Hybrid Privacy-Preserving Deep Learning Approach for Object Classification in Very High-Resolution Satellite Images". Link: https://www.mdpi.com/2072-4292/14/18/4631
 
## Brief Description
This repository is of the approach designed to encrypt High-resolution remote sensing images. It uses a hybrid approach to encrypt the object in remote sensing images. The hybrid PPDL approach utilizes the combination of Partially homomorphic encryption and Somewhat homomorphic encryption from the generated keys. The benefit of this approach is to ensure the privacy of the useful information in the image.

## Model Detail
This model has three steps that are shown below:

![alt text] (https://www.mdpi.com/remotesensing/remotesensing-14-04631/article_deploy/html/images/remotesensing-14-04631-ag-550.jpg)

First step: encrypt the data with the hybrid PPDL.
<br />
Second step: we use  Resnet50, InceptionV3, DenseNet169, and MobileNetV2  to predict the classification of class data
<br />
Thirsd step: the evaluation of the hybrid PPDL is based on some parameters. 

### Requirement
* Python 3.9.0
* scikit-image 0.19.3
* Numpy 1.19.5
* Pillow 9.2.0

### Usage
* Clone the Repository:
```ruby
  git clone https://github.com/Manel-alt-art1/Hybrid-Privacy-Preserving-Deep-Learning.git
```
* Data: 
change the path in the `Hybrid_PPDL.ipynb` file.
* Use the model:
```ruby
  python Hybrid_PPDL.ipynb
```

### Citation

If you use any part of this work please cite using the following Bibtex format:
```
@Article {rs14184631,
AUTHOR = {Boulila, Wadii and Khazri Khlifi, Manel and Ammar, Adel and Koubaa, Anis and Benjdira, Bilel, and Farah, Imed Riadh},
TITLE = {A Hybrid Privacy-Preserving Deep Learning Approach for Object Classification in Very High-Resolution Satellite Images},
JOURNAL = {Remote Sensing},
VOLUME = {14},
YEAR = {2022},
NUMBER = {18},
ARTICLE-NUMBER = {4631},
URL = {https://www.mdpi.com/2072-4292/14/18/4631},
ISSN = {2072-4292},
DOI = {10.3390/rs14184631}
}

'''
