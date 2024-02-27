# Tomato Plant Disease Detection using TinyML

## Description
This project focuses on developing a machine learning model for identifying tomato plant diseases from leaf images. Leveraging TensorFlow Lite and Edge Impulse, we create a compact model suitable for deployment on edge devices. The model enables real-time disease diagnosis, aiding agricultural decision-making.

### Dataset Used - [Plant Disease](https://www.kaggle.com/datasets/emmarex/plantdisease)

## Key Features
- `Dataset`: Plant Village dataset containing `16,011` tomato leaf images across `10` disease categories.
- `Methodology`: Data preprocessing, model development, conversion, deployment, evaluation, and validation.
- `Results`: Achieved accuracy of `89.6%` in disease identification.
- `Expected Outcomes`: High-performing, lightweight ML model, successful deployment on edge devices, real-world effectiveness.
- `Real-World Use`: Real-time plant health prediction via the Edge Impulse app on mobile devices.

## Input Images
![alt text](image-1.png)
## Model
![alt text](image.png)
## Output
![alt text](image-2.png)
![alt text](image-3.png)
![image](https://github.com/its-kumar-yash/Tomato-Plant-Disease-Detection-Model/assets/97521394/1b2f2b2a-c3ef-48f3-a90a-2e36dd7352f4)


## Technology Stack
- TensorFlow
- TensorFlow Lite
- Edge Impulse
- Python

## How to Use
- Clone the repository `git clone https://github.com/its-kumar-yash/Tomato-Plant-Disease-Detection-Model.git`
- Download the dataset.
- Install required dependencies.
- Run the `jupiter notebook`.
- Upload `tf_lite_quantized_model.tflite` file on `Edge Impulse` and Build the model.
