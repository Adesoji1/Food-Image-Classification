# Food-Image-Classification



---

### **GitHub Description**:

🍔 Food Image Classification using TensorFlow: A deep learning model to classify various food items using TensorFlow and CNNs.

---

### **README.md**

### Food Image Classification using TensorFlow

This repository contains a deep learning model that classifies various food items using TensorFlow and Convolutional Neural Networks (CNNs).

## Project Overview

The goal of this project is to build a model that can accurately classify images of food into predefined categories. With the rise of health and fitness apps, such a model can be integrated into applications to automatically detect and log consumed food items based on user-uploaded images.

## Dataset

The dataset used for this project consists of images of various food items categorized into different classes. Each image is labeled with its corresponding food category. Available  [here](https://drive.google.com/drive/u/0/folders/1fTBPKhOU5bTIo6gTmJmvzDXCT5fXUvTz) 

## Features

- **Data Augmentation**: To artificially increase the size of the training dataset and improve model generalization.
- **Convolutional Neural Networks (CNNs)**: Utilized for feature extraction from images.
- **Regularization**: To prevent overfitting and ensure the model generalizes well to new, unseen data.
- **Transfer Learning**: Leveraged pre-trained models to improve accuracy and reduce training time.

## Requirements

- TensorFlow 2.x
- Python 3.7+
- Numpy
- Matplotlib
- Scikit-learn
- hypopt
- PIllow
- torch (During Experimentation)
- pipreqs

## Usage

1. Clone the repository:
```
git clone https://github.com/your_username/food-image-classification.git
```

2. Navigate to the project directory and install the required packages:
```
cd food-image-classification

Use  pipreqs to obtain requirements
```

3. Run the main script  in the orderr represented in the AI Algorithm .ipynb  here on google colab to train the model:
`
4. To evaluate the model on test data, view the test scores in the AI Algorithm.ipyb file:

## Results

The model achieved a test accuracy of 92% on the test dataset. The training and validation loss/accuracy plots can be found in the AI Algotithm file.

## Future Work

- Integrate the model into a mobile application for real-time food classification.
- Expand the dataset to include more diverse food items from various cuisines.
- Experiment with more advanced architectures and techniques to further improve accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Special thanks to the creators of the food dataset.
- TensorFlow documentation and community for valuable resources and discussions.

---


