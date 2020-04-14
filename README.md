# Epilepsy-analysis

This program aims to help analyse the laser speckle contrast images & eeg data of epileptic mouse.

The project is my undergraduate thesis project. And it can help scientists who specialize in electrophysiology and mesoscopic imaging.

## Requirement

Matlab r2019a or higher

you could change the file format by your own.

all data is `16 bit` depth
defaulted raw images format is `.tiff`
defaulted analysed images format is `.tif`

## Usage

### LSCI 

including 3 function: `LSCI_initial` `Images_mean` `Analyse Two Images`

*LSCI_initial

    1. click the botton and choose a raw images of LSCI (all images in the folder would be uploaded)
    2. choose whether you need spatial or temporal speckle contrast images
    3. you can define some paremeters of the sliding window
    4. all results are saved in the folder directory called `LSCI_initial` of your matlab file

#### *Images_mean

This function can help get the average of every pixels in a group of images.

    1. click the botton and choose your images (all images in the folder would be uploaded)
    2. the result is saved in your program folder called 'mean.tif'

#### *Analyse Two Images



Institute: Huazhong University of Science and Technology
           &Zhejiang University

Author: Xianghan Kong   

Teacher: Shangbin Chen & Yicheng Xie



