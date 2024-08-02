# Emotion AI Project ![Emotion AI Graphics](https://img.shields.io/badge/Emotion_AI-Project-FF6F61?logo=python&logoColor=white) ![Emotion AI Header](https://github.com/lechakrawarthy/Emotion_AI/blob/main/header_emotion.png?raw=true) 

Welcome to the **Emotion AI** project! This project is designed to detect emotions from facial expressions using a custom Convolutional Neural Network (CNN) model. Dive into the details below to get started.

---

## 📋 Table of Contents

- [Description](#description) 
- [Features](#features)
- [Prerequisites](#prerequisites) 
- [Installation](#installation) 
- [Usage](#usage)
- [Project Structure](#project-structure) 
- [Contributing](#contributing) 
- [License](#license) 
- [Contact](#contact) 
---

## 📝 Description

This project focuses on detecting human emotions using Convolutional Neural Networks (CNNs) trained on the FER-2013 dataset. By leveraging advanced CNN architectures and employing techniques to handle class imbalance, the project aims to classify emotions accurately and deploy the model for real-time detection in live video streams.

![Emotion Detection](https://github.com/lechakrawarthy/Emotion_AI/blob/main/description_emotion.png?raw=true)

### 🛠️ Key Components:

- **Custom CNN Model**: Trained on a comprehensive dataset for high accuracy.
- **Face Detection**: Utilizes Haarcascades for detecting faces in images.
- **Emotion Classification**: Classifies emotions such as happiness, sadness, surprise, and anger.

---

## 🚀 Features
  Data Augmentation and Class Balancing: Addressed class imbalance in the FER-2013 dataset with image augmentation and class weights to enhance model robustness. Advanced CNN Architectures: Designed and iterated on custom CNN models, optimizing performance with architectures such as VGG16 and ResNet50v2. High Accuracy: Achieved 66% overall accuracy in emotion classification, with detailed performance metrics including precision, recall, and F1-scores for 7 emotion labels. Real-Time Emotion Detection: Deployed the final model using Gradio and OpenCV, enabling dynamic on-screen emotion labels in live video streams.
  
- **Real-time Emotion Detection** 
- **Pre-trained Model** 
- **Easy Setup**

---

## 📋Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.12.4** ![Python](https://img.shields.io/badge/Python-3.12-yellow)
- **Git** ![Git](https://img.shields.io/badge/Git-Installed-lightgrey)
- **Git Large File Storage (LFS)** ![LFS](https://img.shields.io/badge/Git_LFS-Installed-red)
- **Keras** ![keras](https://img.shields.io/badge/keras-Installed-red)
- **OpenCv-Python** ![OpenCv](https://img.shields.io/badge/Open_Cv-Installed-blue)
- **TensorFlow** ![TensorFlow](https://img.shields.io/badge/Tensor_Flow-Installed-orange)
- **Numpy** ![Numpy](https://img.shields.io/badge/Numpy-Installed-blue)
- **Matplotlib** ![Matplotlib](https://img.shields.io/badge/Matplotlib-Installed-lightgrey)
- **Pandas** ![Pandas](https://img.shields.io/badge/Pandas-Installed-darkblue)
- **Gradio** ![Gradio](https://img.shields.io/badge/Gradio-Installed-orange)
- **Kaggle DataSet** ![Kaggle](https://img.shields.io/badge/Kaggle-Installed-blue)
- **[Kaggle_DataSet](https://www.kaggle.com/datasets/msambare/fer2013)**

---

## 🛠️ Installation

### 1. Clone the Repository

Clone the repository to your local machine:

```sh
git clone https://github.com/lechakrawarthy/Emotion_AI.git
cd Emotion_AI
```

### 2. Install Git LFS

If you haven't already, install Git LFS and initialize it:

```sh
git lfs install
```

### 3. Install Python Dependencies

Create a virtual environment and install the required Python packages:

```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

---

## 🏃 Usage

### Running the Project

To run the project, execute the following command:

```sh
python test.py
```

### Example

Here’s how you can use the project:

1. **Prepare an Image:**

   Save your image as `sample_image.jpg` in the project directory.

2. **Run the Script:**

   Process the image with:

   ```sh
   python test.py --image sample_image.jpg
   ```

3. **Output:**

   You will see an output similar to:

   ```plaintext
   Processing image: sample_image.jpg
   Detected Emotions:
   - Happiness: 0.85
   - Sadness: 0.10
   - Surprise: 0.03
   - Anger: 0.02
   ```

   An output image with detected emotions highlighted will be saved as `output_image.jpg`.

---

## 🗂️ Project Structure

Briefly describing the project structure:

```
Emotion_AI/
├── Custom_CNN_model.keras           # Pre-trained model for emotion detection
├── haarcascade_frontalface_default.xml  # XML file for face detection using Haar cascades
├── test.py                          # Main script to run the project
├── requirements.txt                 # File listing Python dependencies
├── README.md                        # Project documentation
└── .gitattributes                   # Git LFS configuration
```

---

## 🤝 Contributing

We welcome contributions! To contribute:

### 1. Fork the Repository

Fork the repository on GitHub.

### 2. Create a New Branch

Create a new branch for your changes:

```sh
git checkout -b feature-name
```

### 3. Make Your Changes

Implement your changes.

### 4. Commit Your Changes

Commit your changes with a descriptive message:

```sh
git add .
git commit -m "Add feature description"
```

### 5. Push to Your Branch

Push your changes:

```sh
git push origin feature-name
```

### 6. Create a Pull Request

Create a pull request from your branch to the main repository, describing your changes in detail.

---

## 📜 License

This project is licensed under the MIT License.See the [LICENSE](LICENSE) file for details.
```sql
MIT License

Copyright (c) [2024] [L E Chakrawarthy Sreenivas]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```


---

## 📫 Contact

For questions or suggestions, reach out to:

- **Name**: L E Chakrawarthy Sreenivas
- **Email**: [chakravarthi1597@gmail.com](mailto:chakravarthi1597@gmail.com)
- **GitHub**: [https://github.com/lechakrawarthy](https://github.com/lechakrawarthy)

Thank you for contributing to the Emotion AI project!

---
