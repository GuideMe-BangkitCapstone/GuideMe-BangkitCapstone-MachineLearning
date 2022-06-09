# GuideMe-BangkitCapstone-MachineLearning
![Wherever you go, you know](https://user-images.githubusercontent.com/69246482/172912779-65b0304c-1b78-4985-92e0-976572356a86.png)

## App Description
This application is built using the python programming language and uses the tensorflow library. This application is used to train a model from the dataset that we have created to classify historical tourist attractions in Indonesia.

- Dataset & Model : https://drive.google.com/drive/folders/1dA02d8ixzEFgwqVM6oP9UgdX-Dj0Vo_R?usp=sharing

## Statistics
### CNN
![image](https://user-images.githubusercontent.com/69246482/172914884-968fa261-fee3-4d0a-b123-54518a9d0488.png)

### Transfer Learning using ResNet50
#### ResNet50 Pretrained Model Summary
![image](https://user-images.githubusercontent.com/69246482/172915117-52b1cd7b-995e-4c3f-ac8e-f0a6dc3eb12e.png)
#### Train with our dataset and tuning hyperparameters
![image](https://user-images.githubusercontent.com/69246482/172914979-3a24433c-c22d-40de-afed-db88da7c9a3c.png)

### Model Evaluation
![image](https://user-images.githubusercontent.com/69246482/172915340-d2aa6243-9ee3-4cb8-a96b-91b82e7da02b.png)

From the results of the model evaluation that we have done above, we agree to use the model from the transfer learning results using ResNet50 because from the evaluation results we get ResNet50 has an accuracy that is not much different from CNN but has a smaller model file size than CNN.
