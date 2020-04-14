# Epilepsy-analysis

This program aims to help analyse the laser speckle contrast images & eeg data of epileptic mouse.

The project is my undergraduate thesis project. And it can help scientists who specialize in electrophysiology and mesoscopic imaging.

## Requirement

Matlab r2019a or higher

you could change the file format by your own.

all LSCI images are `16 bit` depth\
defaulted LSCI raw images format is `.tiff`\
defaulted LSCI analysed images format is `.tif`\
EEG data format is `.continuous`

## Usage

all functions are packaged in the GUI file called `program_export.m`

### LSCI 

including 3 function: `LSCI_initial` `Images_mean` `Analyse Two Images`

* LSCI_initial

This function can help analyse raw iamges of LSCI.
        
        1. click the button and choose a raw images of LSCI (all images in the folder would be uploaded)
        2. choose whether you need spatial or temporal speckle contrast images
        3. you can define some paremeters of the sliding window
        4. all results are saved in the folder directory called LSCI_initial of your matlab file

![](https://github.com/kxhaaa/Epilepsy-analysis/blob/master/demo/LSCI_initial.png)

* Images_mean

This function can help get the average of every pixels in a group of images.

        1. click the button and choose your images (all images in the folder would be uploaded)
        2. the result is saved in your program folder called 'mean.tif'

* Analyse Two Images

This function can help get change of two LSCI images at different time.

        1. click the button, choose your basic image, then choose the analysed image
        2. then wait for image registration and input the index of pixel change you want to analyse
    
![](https://github.com/kxhaaa/Epilepsy-analysis/blob/master/demo/result%20of%20analyse%20two%20images.png)

### EEG
including 2 function: `Power Spectrum` `Epileptic EEG Analysis`

* Power Spectrum

This function can help get power spectrum of eeg data.

        1. click the button, and choose your data
        2. click the start and end point of baseline data with the cursor in the chart
        3. set the sampling frequency and get 4 different types of power spectrum result
 
![](https://github.com/kxhaaa/Epilepsy-analysis/blob/master/demo/power%20spectrum.png) 
 
* Epileptic EEG Analysis

This function can help count the interictal spikes and fast ripples semiautomaticly.

        1. click the button and choose the EEG file
        2. set the start and end point of baseline data
        3. set the type of signal. 0 for interictal spike, 1 for fast ripple.
        4. click the start and end point of baseline data with the cursor in the chart
        5. set the coefficient of baseline and the spike distance
        6. click the start and end point of the experiment data with the cursor in the chart 
        7. the total number of spikes is displayed on the screen, and the recording spikes are marked on the chart
        
### Protein Overlap rate

This function can help calculate the percentage of overlap part of two different protein.

        1. click the button and choose two images
        2. choose whether they need autothreshold
        3. the results are displayed on the screen


## Contributing
Institute: Huazhong University of Science and Technology
           &Zhejiang University

Author: Xianghan Kong   

Teacher: Shangbin Chen & Yicheng Xie

Thanks Peng Xu who do the biological experiment and provide me all the data!



