   # Pneumonia Prediction Using Hybrid Neural Networks
   
   ## Project Description
   
   **Pneumonia Prediction Using Hybrid Neural Networks** is a deep learning project aimed at improving the accuracy of pneumonia diagnosis from chest X-ray images. This project integrates three advanced convolutional neural network (CNN) architectures—DenseNet201, InceptionResNetV2, and ResNet50—into a hybrid model to leverage their strengths for superior performance in detecting pneumonia.
   
   ### Key Features
   - **Hybrid Model**: Combines DenseNet201, InceptionResNetV2, and ResNet50 to enhance diagnostic accuracy.
   - **High Accuracy**: Achieves a training accuracy of 99.99% and a validation accuracy of 95.67%.
   - **Advanced Techniques**: Utilizes feature concatenation, learning rate scheduling, and data augmentation for improved model performance.

   ### Model Performance

| Model Name            | Precision | Recall | Accuracy | F1 Score |
| :-------------------- | --------- | ------ | -------- | -------- |
| DenseNet201           | 0.52      | 0.56   | 83.81    | 0.55     |
| InceptionResNetV2     | 0.53      | 0.58   | 80.61    | 0.56     |
| ResNet50              | 0.765     | 0.625  | 62.50    | 0.69     |
| Hybrid(Stacked)       | 0.845     | 0.750  | 95.67    | 0.792    |


![Screenshot 2024-08-19 233941](https://github.com/user-attachments/assets/e24a0cf0-2dac-4838-8e28-f46c58cc656d)


   
   ## Installation
   
   To set up the project environment, follow these steps:
   
   1. **Clone the Repository**
   
      ```bash
      git clone https://github.com/yourusername/pneumonia-prediction.git
      cd pneumonia-prediction
   2. **Create a Virtual Environment**
      ```bash
      python -m venv venv
   3. **Activate the Virtual Environment**
      On windows :
         ```bash
         venv\Scripts\activate
   
   4. **Install Dependencies**
   
      ```bash
      pip install -r requirements.txt
   
   
    ## Additional Information
   
   For more details on the project and related research, please visit [this IEEE link](https://ieeexplore.ieee.org/document/10425735).
     
