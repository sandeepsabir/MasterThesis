# MasterThesis
Detection of unexpanded sealing of the battery lids of the cars for Volvo Cars.

This is my master thesis project titled "Detection of unexpanded sealing of the battery lid of the cars: Using supervised and unsupervised learning algorithms", which is done for the company Volvo Car AB. The pdf version of the thesis project can be downloaded [here](https://his.diva-portal.org/smash/record.jsf?pid=diva2:1882730 "Download Thesis").

In DS_Final_Project1_PreprocessingWIthTemplateMatching.ipynb, preprocessing of the videos captured and the template matching of the frames with the battery lid parts are done to extract battery lids from the video frames.
In DS_Final_Project2_GaborFillterAndThresholding.ipynb, Gabor Filter, and thresholding methods like Adaptive Mean Thresholding and Adaptive Gaussian Thresholding are done.
In DS_Final_Project3_CompareExpandedWithUnexpanded.ipynb, the image of the battery lid just after applying the sealing is compared with the image of the battery lid after one minute of applying the sealing to check the expansion of the battery lids. Structural Similarity Index Measure (SSIM) is used for the comparison.
In DS_Final_Project4_Labelling.ipynb, the images of the battery lids are labelled as Expanded and Unexpanded, which are used for training with supervised machine learning models like Convolutional Neural Network (CNN) and Random Forest (RF).
In DS_Final_Project5_BuildingModel_CNN.ipynb, modelling is done using CNN.
In DS_Final_Project6_BuildingModel_RandomForest.ipynb, modelling is done using RF.
