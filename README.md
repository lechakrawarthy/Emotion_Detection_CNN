---

# Emotion AI Project ![Emotion AI Graphics](https://img.shields.io/badge/Emotion_AI-Project-FF6F61?logo=python&logoColor=white) ![Emotion AI Header](https://github.com/lechakrawarthy/Emotion_AI/blob/main/header_emotion.png?raw=true) 

Welcome to the **Emotion AI** project! This project is designed to detect emotions from facial expressions using a custom Convolutional Neural Network (CNN) model. Dive into the details below to get started.

---

## Table of Contents

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

## Description

This project leverages cutting-edge machine learning techniques to analyze facial expressions and detect emotions. It utilizes a custom-trained CNN model, implemented in Python with the Keras library, to provide accurate emotion recognition. Perfect for real-time applications and research purposes!

![Emotion Detection](https://github.com/lechakrawarthy/Emotion_AI/blob/main/description_emotion.png?raw=true)

### Key Components:

- **Custom CNN Model**: Trained on a comprehensive dataset for high accuracy.
- **Face Detection**: Utilizes Haarcascades for detecting faces in images.
- **Emotion Classification**: Classifies emotions such as happiness, sadness, surprise, and anger.

---

## Features

- **Real-time Emotion Detection** 
- **Pre-trained Model** 
- **Easy Setup**

---

## Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.2.17** ![Python](https://img.shields.io/badge/Python-3.x-blue)
- **Git** ![Git](https://img.shields.io/badge/Git-Installed-lightgrey)
- **Git Large File Storage (LFS)** ![LFS](https://img.shields.io/badge/Git_LFS-Installed-blue)
- **Keras** ![keras](https://img.shields.io/badge/keras-Installed-blue)
- **OpenCv-Python** ![OpenCv](https://img.shields.io/badge/Open_Cv-Installed-blue)
- **TensorFlow** ![TensorFlow](https://img.shields.io/badge/Tensor_Flow-Installed-blue)
- **Numpy** ![Numpy](https://img.shields.io/badge/Numpy-Installed-red)
- **Matplotlib** ![Matplotlib](https://img.shields.io/badge/Matplotlib-Installed-green)
- **Pandas** ![Pandas](https://img.shields.io/badge/Pandas-Installed-green)
- **Gradio** ![Gradio](https://img.shields.io/badge/Gradio-Installed-green)
- **Kaggle DataSet** ![Kaggle](https://img.shields.io/badge/Kaggle-Installed-green)
- **[Kaggle_DataSet](https://www.kaggle.com/datasets/msambare/fer2013)**

---

## Installation

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

## Usage

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

## Project Structure

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

## Contributing

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

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For questions or suggestions, reach out to:

- **Name**: L E Chakrawarthy Sreenivas
- **Email**: [chakravarthi1597@gmail.com](mailto:chakravarthi1597@gmail.com)
- **GitHub**: [https://github.com/lechakrawarthy](https://github.com/lechakrawarthy)

Thank you for contributing to the Emotion AI project!

---

This version maintains clarity, includes graphics, and icons appropriate for each section while ensuring that images and icons render correctly.
