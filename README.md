# Kidney Disease Classification
![](https://github.com/Devesh061102/10-Kidney-Disease-Classification-DL/blob/main/Screenshots/Screenshot%202024-06-15%20104908.jpg?raw=true)

![](https://github.com/Devesh061102/10-Kidney-Disease-Classification-DL/blob/main/Screenshots/Screenshot%202024-06-15%20105020.jpg?raw=true)

## Objective
The main objective of this project is to develop a predictive model to classify kidney images and determine whether a tumor is present or not.

## Data Collection
The project starts with collecting a dataset of kidney images for tumor classification.

## Dataset
The dataset used includes images of kidneys, with labels indicating the presence or absence of a tumor. The images are used to train and evaluate the classification model.

## Preprocessing
- Inspecting data for missing values and duplicates
- Cleaning data and ensuring images are correctly labeled
- Descriptive statistics and initial visualizations

## Exploratory Data Analysis (EDA)
- Distribution analysis of image labels
- Analyzing sample images to understand variations and patterns
- Visualizing image data and labels to identify any imbalances or anomalies

## Model Training
- **Data Preparation:** Splitting the dataset into training, validation, and test sets. Augmenting images to increase dataset diversity.
- **Model Selection:** Using transfer learning to download the pre-trained VGG16 model and fine-tuning it on the kidney tumor dataset.
- **Model Training:** Training specific layers of the VGG16 model on the dataset to improve classification accuracy.
- **Model Evaluation:** Using metrics like Accuracy, Precision, Recall, and F1-Score to evaluate model performance.

## Evaluation
The VGG16-based model is evaluated based on its classification performance, and the best-performing model is selected for deployment.

## Model Deployment
The best-performing model is deployed using Flask, a lightweight web server gateway interface (WSGI) web application framework. This allows the model to be accessed via a simple web interface, enabling users to upload kidney images and receive real-time classification results indicating the presence of a tumor.

## Lessons Learned
This project provided a valuable opportunity to apply deep learning concepts to a practical problem. Key lessons learned include:
- The importance of data cleaning and preprocessing in ensuring accurate analysis
- How to use transfer learning and fine-tune pre-trained models for specific tasks
- How to use tools like DVC and ML Flow to make your work easier 

I’m excited about the potential applications of this project and look forward to exploring more ways to leverage deep learning in the field of medical image analysis and disease diagnosis. 🏥

## Authors
- [Devesh](https://github.com/Devesh061102)