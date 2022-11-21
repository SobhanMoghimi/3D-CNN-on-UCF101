# 3D-CNN-on-UCF101
This repository contains Action Recognition using 3D-CNN model on UCF101 dataset.
The model is trained with Tensorflow and Kears backend. 

## Model
The model is  sequential. It uses numpy dataset as input which is not very good for large datasets, but works good on UCF-101.
![Model Loss](https://github.com/SobhanMoghimi/3D-CNN-on-UCF101/blob/main/Model-Details.png)

## Results
![Model Loss](https://github.com/SobhanMoghimi/3D-CNN-on-UCF101/blob/main/model_loss.png)


![Model Loss](https://github.com/SobhanMoghimi/3D-CNN-on-UCF101/blob/main/model_accuracy.png)


The text file `result.txt` contains all details for each epoch; containing **Train Loss**, **Train Accuracy**, **Validation Loss**, **Validation Accuracy**.

To run the model on your own dataset, just change the num_classes and data paths.
