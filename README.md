# COVID-19 Chest X-Ray Image Classification

![COVID-19 Chest X-Ray Image Classification](https://github.com/FerasAlshash/COVID-19-CXR-CNN/blob/main/-UGefUPBG_YwjwHrVq_io.jpg)

# Workflow:
![COVID-19 Chest X-Ray Image Classification](https://github.com/FerasAlshash/COVID-19-CXR-CNN/blob/main/napkin-selection.png)

This project is a machine learning model designed to classify chest X-ray images into three categories: **COVID-19**, **Normal**, and **Other Viral Infections**. Using convolutional neural networks (CNNs) and image preprocessing techniques, the model achieves high accuracy in distinguishing these categories.

## Project Description

The purpose of this project is to support medical professionals in the early detection of COVID-19 and related conditions through automated chest X-ray image analysis. The dataset used includes labeled grayscale images of X-rays, preprocessed for optimal model performance.

### Key Features
- **Data Preprocessing**: Converts images to grayscale, resizes them to 128x128 pixels, and normalizes pixel values.
- **Augmentation**: Applies rotation, zoom, horizontal flips, and other transformations to enhance generalization.
- **Model Architecture**: Custom CNN with Leaky ReLU activation, dropout layers, and L2 regularization for robust performance.
- **Evaluation Metrics**: Accuracy, Precision, Recall, and F1-Score to assess model performance.

## Project Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/FerasAlshash/COVID-19-CXR-CNN.git
   
   ```


2. Prepare the dataset:
   - Ensure the dataset is structured with labeled folders (`covid`, `normal`, `virus`).
   - Modify the `data_dir` variable in the script to point to your dataset location.



## Results

The model was trained on 150 epochs with early stopping and achieved notable validation accuracy and F1-Score. It effectively classifies X-ray images into the three predefined categories.

## Repository Structure

```
covid-xray-classification/
├── data/
│   ├── covid/
│   ├── normal/
│   ├── virus/
├── scripts/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
├── models/
│   ├── model.h5
├── README.md
├── requirements.txt
```



## Acknowledgments

- Dataset provided by https://www.kaggle.com/code/ferasalshash/covid-19-cxr-cnn.
- Inspired by the guidance of the machine learning community, with heartfelt thanks to my mentor, Ola El-shiekh, whose invaluable insights and support have been a true source of inspiration.
## Contact

For inquiries, please contact:
- **Feras Alshash**: ferasalshash@gmail.com
- https://github.com/FerasAlshash
