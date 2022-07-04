# Melanoma Skin Cancer Detection

![Uniroma1 svg](https://user-images.githubusercontent.com/60270854/177061313-c1c5d83b-85b9-4e3e-b92e-fe58ef13c0f8.png)

### Project By:
 - Saud Hussain (1990559)
 - Raja Asim Fayyaz (1988888)
 - Rida Amjad (1684582)

## Summary
  * Introduction
  * Dataset
  * Prerequisites 
  * Results
  
## Introduction
  Melanoma Skin Cancer is one of the deadlist type of skin cancer, if not detected in early stages. Studies show that melanoma has been responsible for 75% of skin cancer deaths.
  The Melanoma comes from melanocyte cells, melanin-producing cells, so that melanomas are generally brown or black colored. The diagnoses of melanoma cancer are often perfomed manually by visuals of skilled docters and analyzing the dermoscopy images.
  But this approach requires high skillness and thus takes alot of time. 
  
  In this Project we are using CNN (Convulational Neural Network) model, Transfer Learning and Vision Transformer approach to detect the melanoma skin cancer. 
  The results obtained are quite efficient in detecting the melanoma cancer classes from the given data.
  
  
## Dataset:
   The dataset to train, validate and test our model has been taken from "www.isic-archive.com".
   To download the dataset:
   - Uncomment line "#!wget https://isic-challenge-data.s3.amazonaws.com/2020/ISIC_2020_Training_JPEG.zip" in EDA Analysis File.
   
## Pre-Requisies to Run the Project
  1- To run the project online you can can use Google Colab.
  
  2- TO run the project offline you ned to have the following.
  
        - Python3
        - Jupyter pip install jupyterlab
        - Tensorflow (via conda or pip)
        - Numpy pip install numpy
        - Pandas pip install pandas
        - Matplotlib pip install matplotlib
        - Seaborn pip install seaborn
        - OpenCV pip install opencv-python
        - Scikit Learn pip install scikit-learn
        
## Results:
### CNN Model
Classification Report:

![image](https://user-images.githubusercontent.com/60270854/177062040-1ef1816c-788b-4e90-9778-98b226007013.png)

### Transfer Learning (Xception)
Classification Report:

![image](https://user-images.githubusercontent.com/60270854/177062100-20cd052e-294e-4e63-95c1-4b63463dd5be.png)

## Vision Transformer
Classification Report:

![image](https://user-images.githubusercontent.com/60270854/177062727-bd7969e0-e16b-4245-88b9-ac1c528f4e1f.png)


| Model         | Accuracy      | F1-Score |
| ------------- | ------------- | -------- |
| CNN          | 93%         | 93%  |
| Transfer Learning (Xception) | 99% | 99%         | 
| Vision Transformer |   94%      |  94%       | 


