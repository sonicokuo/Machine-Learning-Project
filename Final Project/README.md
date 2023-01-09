# Intro. to Machine Learning Final Project

This repository is the implementation of [My Final Project](https://docs.google.com/presentation/d/15d4W_8GFks4Mqmf4kvmTxYC8tJv-KNg6c8rQrlccEWM/edit#slide=id.g61dd2f3d9d_2_83). 

>Train a ML model to predict product failures by a large testing study
>![image](https://user-images.githubusercontent.com/73321093/211354178-0e9fe753-3f2e-4c9e-9a2b-e61c15a65b40.png)


## Environment Setup

To install required libraries, 
please download [0816170_Final_train.ipynb](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_Final_train.ipynb) and 
[0816170_Final_inference.ipynb](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_Final_inference.ipynb), 
and then run the first blocks of them on [Google Colab](https://colab.research.google.com/)

>![image](https://user-images.githubusercontent.com/73321093/211354767-61a183ec-818c-4a3a-8382-8e5c18291089.png)

## Training

To train the model(s) in the final project, run 
[0816170_Final_train.ipynb](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_Final_train.ipynb) on 
[Google Colab](https://colab.research.google.com/).

>Note that you should also download [test.csv](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/test.csv) and 
[train.csv](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/train.csv) and change data paths (as the picture shown below) according to the file paths in your Google Drive.  
>![image](https://user-images.githubusercontent.com/73321093/211357749-9d256e73-6dfd-4f89-8a31-2d81f0218652.png)

After you run the code, a trained model will be dumped to your Google Drive.
The model should be the same as [0816170_model.pkl](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_model.pkl).
>You may change file path to dump the model to your desired folder (as the picture shown below).
>![image](https://user-images.githubusercontent.com/73321093/211359735-dcfd3f5c-2dc0-44a5-b40d-a2693424d923.png)

## Pre-trained Model

You can download a pretrained model here:

- [My model](https://drive.google.com/file/d/1yeSTK_EhuhrMZyoYPtWmcT_G8WK3QmT-/view?usp=sharing) stored in my Google Drive
- or
- [0816170_model.pkl](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_model.pkl) on GitHub (they are the same)

## Inferencing

To inference predictions with the model, run 
[0816170_Final_inference.ipynb](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170_Final_inference.ipynb), 
on [Google Colab](https://colab.research.google.com/).


>Note that you should also download [test.csv](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/test.csv) and 
[train.csv](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/train.csv) and change data paths (as the picture shown below) according to the file paths in your Google Drive.  
>![image](https://user-images.githubusercontent.com/73321093/211357749-9d256e73-6dfd-4f89-8a31-2d81f0218652.png)
>
>Besides, please change the file path of the model which you are going to use, and you may change file path to output the prediction (i.e. 0816170.csv) to your desired folder (as the picture shown below).
>![image](https://user-images.githubusercontent.com/73321093/211361906-bb7ae4b1-8b55-4d4f-86a6-3e31fe227c7b.png)


After you run the code, the prediction will be outputted to your Google Drive.
The prediction should be the same as [0816170.csv](https://github.com/sonicokuo/Machine-Learning-Project/blob/master/Final%20Project/0816170.csv).
>The prediction shoud be a csv file with 20776 rows (as the picture shown below).
>
>![image](https://user-images.githubusercontent.com/73321093/211368328-4ac645f5-85b9-4568-bf00-ac028e7f1bc8.png) 
![image](https://user-images.githubusercontent.com/73321093/211367826-ed062569-a2d9-4b37-9314-6406064a125e.png)





## Results

My model achieves the following performance on :

### [Tabular Playground Series - Aug 2022](https://www.kaggle.com/competitions/tabular-playground-series-aug-2022)
*Late Submission

>![image](https://user-images.githubusercontent.com/73321093/211366222-303a3c52-c6ab-49af-8da2-9bbc7f8a1746.png)
