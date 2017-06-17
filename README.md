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
1. For a complete training
* Download the Jupyter notebook "gender_prediction.ipynb" and save it to a specific path (called GD_PATH)
* In GD_PATH, create folder gender/wiki_crop
* Download the processed [WIKI dataset](https://drive.google.com/open?id=0BxINLo5jshCRYW8xODhNSlkyLTQ) [1] and save them to GD_PATH/gender/wiki_crop
* Download [additional testing images](https://drive.google.com/open?id=0BxINLo5jshCRUHNNVjd1QVA4bmM) and store them in GD_PATH
* Open "gender_prediction.ipynb" with Jupyter and run all cells
2. For testing using trained model
* ...

### References
[1] Rasmus Rothe, Radu Timofte, and Luc Van Gool, "Deep expectation of real and apparent age from a single image without facial landmarks," International Journal of Computer Vision (2016)

### Personal information
Nguyen Hai Duong  
Pattern Recognition Lab  
Chonnam National University, Korea  
E-mail: nhduong_3010@live.com