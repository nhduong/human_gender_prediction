# Human Gender Prediction
Chonnam National University  
2017 AI Class  
Prof. Lee Chilwoo  
Student: Nguyen Hai Duong  
**Target: predict human gender using Convolutional Neural Network**

## Gender prediction examples
![alt text](https://raw.githubusercontent.com/nhduong/2017_ai_cource_project/master/imgs/1.PNG)

## Confusion matrix on Wiki testing set
![alt text](https://raw.githubusercontent.com/nhduong/2017_ai_cource_project/master/imgs/confusion_matrix.png)

## Requirements
1. TensorFlow 1.1.0 (or later)
2. Python 2.7/3.5
3. Jupyter Notebook
## How to run source code
### For a complete training
1. Download the Jupyter notebook `gender_prediction.ipynb` and save it to a specific path (called **GD_PATH**)
2. In **GD_PATH**, create folder **gender/wiki_crop**
3. Download the processed [WIKI dataset](https://drive.google.com/open?id=0BxINLo5jshCRYW8xODhNSlkyLTQ) [1] and save them to **GD_PATH/gender/wiki_crop**
4. Download [additional testing images](https://drive.google.com/open?id=0BxINLo5jshCRUHNNVjd1QVA4bmM) and store them in **GD_PATH**
5. Open `gender_prediction.ipynb` with Jupyter and run all cells
### For testing using trained model
1. Download the Jupyter notebook `gender_prediction_testing.ipynb` and save it to a specific path (called **GD_PATH**)
2. Download [trained model](https://drive.google.com/open?id=0BxINLo5jshCRTTcwdjdKRVFTRUU) on WIKI dataset [1] and save it to **GD_PATH**
3. In **GD_PATH**, create folder **gender/wiki_crop**
4. Download [WIKI testingset](https://drive.google.com/open?id=0BxINLo5jshCRYW8xODhNSlkyLTQ) [1] including **64_64_11938_4098_testing_x_onehot.npy**, and **64_64_11938_4098_testing_y_onehot.npy** and store them in **GD_PATH/gender/wiki_crop**
5. Open `gender_prediction_testing.ipynb` with Jupyter and run all cells

### References
[1] Rasmus Rothe, Radu Timofte, and Luc Van Gool, "Deep expectation of real and apparent age from a single image without facial landmarks," International Journal of Computer Vision (2016)

### Personal information
Nguyen Hai Duong  
Pattern Recognition Lab  
Chonnam National University, Korea  
E-mail: nhduong_3010@live.com