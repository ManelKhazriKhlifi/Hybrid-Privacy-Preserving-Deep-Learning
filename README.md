# A Hybrid Privacy-Preserving Deep Learning Approach for Object Classification in Very High-Resolution Satellite Images
This repository contains the code for the following publication "A Hybrid Privacy-Preserving Deep Learning Approach for Object Classification in Very High-Resolution Satellite Images". Link: https://www.mdpi.com/2072-4292/14/18/4631
 
## Brief Description
This repository is the approach designed to encrypt high resolution remote sensing imagery. It uses a hybrid approach to encrypt remote sensing datasets. The hybrid PPDL approach uses the combination of partially homomorphic encryption and somewhat homomorphic encryption from generated keys. The advantage of this approach is to ensure the confidentiality of useful information in the image.

## Dataset Details
Remote sensing data from seven cities in Saudi Arabia (Al Madinah, Riyadh, Jeddah, Al Qassim, Al Qatif, Hail and Dammam) were divided into non-overlapping 256x256 blocks. These images are encrypted by the proposed approach. After encrypting them, this dataset is used to train four CNN models. 

## Model Details
This model has three steps that are shown below:

![tree](GA.png)

The first step shows the structure of data encryption with hybrid PPDL.
<br />
The second step shows the classification of encrypted remote sensing data with CNN models.
<br />
The third step shows the evaluation of the hybrid PPDL according to some parameters. 

### Requirement
* Python 3.9.0
* scikit-image 0.19.3
* Numpy 1.19.5
* Pillow 9.2.0
* tensorflow

### Usage
* Clone the Repository:
```ruby
  git clone https://github.com/Manel-alt-art1/Hybrid-Privacy-Preserving-Deep-Learning.git
```
* Data: 
change the path in the `Hybrid_PPDL.ipynb` file.
* Use the model:
```ruby
   Hybrid_PPDL.ipynb
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

