# Detecting COVID-19 in CT Images
This repo contains a pre-trained model for detecting Covid-19 in CT images.


# Overview:
Applying deep learning techniques on the CT scan images of COVID-19
patients would not only assist in disease diagnosis, but also help in quantifying
the severity of the illness, and hence, prioritize the population treatment
accordingly. Here I suggest techniques that prove to be reliable as
detectors for infected tissue in lung CT scans. The importance of such a
method in today’s pandemic would help automate, prioritize, fasten, and
broaden the treatment of COVID-19 patients globally until the completion of
vaccinating process.
In this project I provide a tool based on deep learning algorithm in order to help doctors in
detecting the COVID-19 in CT scans images.

# Dataset:
In this project I use a dataset containing 1252 CT scans that are positive for SARS-CoV-2
infection (COVID-19) and 1230 CT scans for patients non-infected by SARS-CoV-2, 2482 CT
scans in total. These data have been collected from real patients in hospitals from Sao Paulo,
Brazil. 

Download link: https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset

# Requirements:
This model is built using Python 3.7. I highly recommend you to use GPU version of tensorflow, training this model is very slow in CPU mode.

- tensorflow
- seaborn
- sklearn
- pandas
- numpy
- matplotlib

# Reference:
A large dataset of real patients CT scans for SARS-CoV-2 identification." medRxiv (2020)

doi: https://doi.org/10.1101/2020.04.24.20078584.

# Contact
m.taleb.albrijawi@std.medipol.edu.tr
