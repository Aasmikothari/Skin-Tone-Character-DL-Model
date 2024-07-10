*Implementation of a Deep Learning Model to Evaluate and Comment on Skin Tone Characteristics on Alzheimer’s perspective*

A sophisticated deep learning system designed to analyze and interpret skin tones in digital images. 
The primary objective is to create a model capable of recognizing and classifying a wide range of skin tones with high precision. 
By focusing on accurately capturing subtle nuances and variations in skin tones, the system seeks to improve the reliability and accuracy of skin tone recognition by utilizing the HAM10000 dataset, which consists of dermatoscopic images for melanoma and other skin lesion classifications. 
The skin malfunction holds a noticeable effect on Alzheimer’s disease. 
The developed model will analyze the input images using the specific HAM10000 dataset, providing detailed comments on the similarity and classification of each skin lesion. 
The results will highlight the accuracy of the model in identifying and categorizing various types of skin conditions, demonstrating its capability to distinguish subtle differences in skin tones and lesions with high precision.

![image](https://github.com/Aasmikothari/Skin-Tone-Character-DL-Model/assets/90106410/64b4fe92-acf6-4357-a992-402f7b5f488a)

*The proposed flow process of the deep learning model is shown in Fig. 1 and is outlined for its implementation below:*

1.	Import essential libraries: This step involves importing libraries pandas, numpy and warnings.

2.	Loading data and making labels:  The data is loaded from HAM10000.csv file and is read.

3.	Train Test Split: In this step the read data is then trained and tested by their labels.

4.	Exploratory data analysis (EDA): This step involves importing seaborne, randomoversampler, pyplot, to plot random images from the dataset.

5.	Model Building (CNN): The model building includes importing sequential, flatten, dense, from tensorflow to classify and connect each image from the dataset in a convolutional format.

6.	Setting optimizer and Annealing: This step uses callback from tensorflow to train the data at any given moment.

7.	Fitting the model: Fitting performs importing datetime from datetime and fit the model to the trained data.

8.	Model evaluation: It imports plt to plot the accuracy and loss from the above step and then import PIL to import another image from another dataset and classify it to the trained data to analyze and comment on the label of classification of skin lesions accordingly.

*IMAGES:* 

![image](https://github.com/Aasmikothari/Skin-Tone-Character-DL-Model/assets/90106410/43f9644f-caeb-4149-a6f8-d38bd3168b51)
![image](https://github.com/Aasmikothari/Skin-Tone-Character-DL-Model/assets/90106410/e51bb122-8e51-4285-8474-8fd8d241ebf8)

