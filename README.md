# Deep Learning a gyakorlatban Python és LUA alapon
## Homework 3

Created by: Viktor Nagy (JBV582)

This is my solution to the third homework of the course. This repository contains a deep feedforward neural network for predicting the mean daily temperature of Budapest. To complement my work on the semester-long assignment – music generation from waveform or spectrogram – I used an architecture developed for time series prediction: WaveNet. I built upon and modified a [basic Keras implementation by peustr](https://github.com/peustr/wavenet) of the original WaveNet as [published by Deep Mind](https://arxiv.org/pdf/1609.03499.pdf). My changes are described in the Jupyter Notebook along the code. 

110 years of daily temperature measurements was downloaded as training data from the [OMSZ webpage](https://www.met.hu/eghajlat/magyarorszag_eghajlata/eghajlati_adatsorok/Budapest/adatok/napi_adatok/index.php). Testing data was complied from 106 [idojarasbudapest.hu](http://idojarasbudapest.hu/archivalt-idojaras) queries.

This repository contains a Jupyter Notebook with code and documentation inside, training and testing data and a pretrained model that can predict the next day's mean temperature from 512 previous days' data.
