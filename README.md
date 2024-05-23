# Cat Detection with Computer Vision

This repository contains the code and resources for the Cat Detection Challenge using the YOLOv8 object detection architecture.

## Introduction

The goal of this project is to identify and locate cats in images using YOLOv8. The process includes data preprocessing, model training, validation, and inference.

## Repository Structure

- `Desafio_Gabriel_Fernandes_Carvalho.ipynb`: Main notebook containing the full workflow.
- `cats_dataset/`
  - `features/`: Extracted features from images.
  - `imgs/`: Images for training.
  - `inference_imgs/`: Images for inference.
  - `labels/`: Image annotations.

## Environment Setup

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/cat-detection-challenge.git
    cd cat-detection-challenge
    ```

2. Install the required packages:
    ```bash
    pip install ultralytics
    pip install -U ipywidgets
    ```

## Usage

1. **Run the Notebook**:
   - Open and run the `Desafio_Gabriel_Fernandes_Carvalho.ipynb` notebook.

2. **Inference with New Images**:
    - Place the images in the `cats_dataset/inference_imgs/` folder.
    - Execute the inference section in the notebook to see the results.

## Results

The detection results are saved in the `images/` folder and include visual examples of bounding boxes around the detected cats.
