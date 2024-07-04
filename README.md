# Butterfly Classifier Project

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [License](#license)

## Overview

This project is a Butterfly Classifier developed for the course Machine Learning & Artificial Intelligence of the Master's degree program in Computer Engineering for Robotics and Smart Industry for the academic year 2023/2024. The project leverages various machine learning classification models such as Support Vector Machines (SVM) and k-Nearest Neighbors (KNN), and employs feature extraction techniques like Principal Component Analysis (PCA). Additionally, the VGG neural network is used in combination with SVM and KNN.

The primary objective of this project is to study which models best classify butterflies depending on the type of image preprocessing: RGB colored images, black and white images, and HSV images.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SofiaFranceschi/Butterfly-Classifier.git
    cd Butterfly-Classifier
    ```

2. Install the required Python packages:
    ```bash
    pip3 install -r requirements.txt
    ```

## Dataset

The dataset used for this project is sourced from Kaggle and contains images of 100 different butterfly species. It is pre-split into training and testing sets.

- Dataset URL: [Butterfly & Moths Image Classification 100 species](https://www.kaggle.com/datasets/gpiosenka/butterfly-images40-species)

Download the dataset and extract the contents. From the `.zip` file, extract only the `train` and `test` folders, and the file `butterflies and moths.csv`. Place these items at the same level as the `classifier_main.ipynb` file. The directory structure should be as follows:
```
📁 ML_progetto
└── butterflies and moths.csv    # CSV file with additional data
└── classifier_main.ipynb        # Main notebook for running the project
└── README.md                    # Project README file
└── requirements.txt             # List of required Python packages
└── 📁 test
└── 📁 train
```

## Usage

To run the classifier, execute the main Jupyter Notebook file:

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open and run all cells in the `classifier_main.ipynb` notebook.

This notebook contains all the necessary code to train the model, evaluate its performance, and make predictions on new butterfly images.

## Project Structure

The repository is structured as follows:
```
📁 ML_progetto
└── butterflies and moths.csv    # CSV file with additional data
└── classifier_main.ipynb        # Main notebook for running the project
└── README.md                    # Project README file
└── requirements.txt             # List of required Python packages
└── 📁 test
└── 📁 train
```

## Results

The performance of the classifier is evaluated using standard metrics such as accuracy, precision, recall, and F1-score. Detailed results, including confusion matrices and visualizations of correctly and incorrectly classified images, are available in the `classifier_main.ipynb` notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


