# Skin Cancer Classification System

This repository contains the code for a Skin Cancer Classification System using Deep Learning. The goal of the project is to classify pigmented skin lesions and detect skin lesions in images. The project utilizes the HAM10000 dataset for research purposes.

<p align="center">
  <img src="https://github.com/ali0salimi/cucumber-leaf-disease-prediction/blob/main/dataset_sample.png" alt="Project Demo" width="800">
</p>

## Table of Contents

- [Project Overview](#project-overview)
- [Key Steps](#key-steps)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The main objective of this project is to develop a system capable of classifying and detecting pigmented skin lesions  in images using Deep Learning techniques. The project pipeline involves several steps including image segmentation using a pretrained U-Net model and subsequent training of an FRCNN (Faster R-CNN) model for classification and detection tasks.

## Key Steps

1. **Data Preprocessing and Segmentation**: The HAM10000 dataset is preprocessed and segmented using a pretrained U-Net model to extract skin lesions from the images.

2. **Bounding Box Extraction**: Bounding boxes are generated from the segmented images, which provide the region of interest for further analysis.

3. **FRCNN Model Training**: An FRCNN model is trained using the segmented images and corresponding bounding boxes. This model is used for both classifying and detecting skin lesions.

4. **Evaluation and Results**: The trained FRCNN model is evaluated on a test set, and the results are documented. Metrics such as accuracy, precision, recall, and F1-score are reported.

5. **Deployment**: If applicable, this section can cover how to deploy and use the trained model for real-world applications.

## Installation

Provide instructions here on how to install any dependencies and set up the environment needed to run your project.

## Usage

Explain how to use your code and scripts to replicate the experiments or results. Include command examples, arguments, and any other relevant information.

## Dataset

Briefly describe the HAM10000 dataset and provide a link to where it can be accessed or downloaded.

## Results

You can mention key results, metrics achieved by your model, and any visuals that showcase the performance of your system.

## Contributing

Explain how others can contribute to your project. Whether it's bug fixes, new features, or improvements, provide clear instructions for potential contributors.

## License

Specify the license under which your project is released. For example, you can use a license badge like [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE).

---
Feel free to customize the sections and content according to your project's specific needs. Remember to add any relevant images, code snippets, or diagrams to make your README more informative and visually appealing.
