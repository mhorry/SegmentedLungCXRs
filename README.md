# SegmentedLungCXRs
A Repository of Segmented Lung CXRs (PA view) for Unbiased Training of Deep Learning Models

One of the key challenges in building machine learning models for CXRs is the variabillity in the quality of the images within and between sources, especially where certain conditions (such as COVID-19) are primarily located at a single source being https://github.com/ieee8023/covid-chestxray-dataset.  

We don't want our AIs to be mistrained by systematic differences in brightness/contrast and other attributes assocuated with the image source rather than the clinical conditions that we are interested in so we are developing a pipeline that normalizes the images through histogram equalization and segments the lung/diapraghm area from the rest of the frame to reduce signal noise.

This is the dataset used for "X-Ray Image based COVID-19 Detection using Pre-trained Deep Learning Models" avaiable as a pre-print here https://engrxiv.org/wx89s/ 
