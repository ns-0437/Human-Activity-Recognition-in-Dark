
# Project Title
Human Activity Recognition in Dark

## Description
This project implements a Human Activity Recognition (HAR) system using a Long-term Recurrent Convolutional Network (LRCN). The notebook includes functionality for extracting video frames, preparing datasets, building the LRCN model, and visualizing training metrics.

## Features
- **Frame Extraction**: Efficiently extract frames from video data.
- **Dataset Creation**: Prepare a dataset suitable for training and evaluation.
- **Model Implementation**: Build and train an LRCN model using TensorFlow.
- **Visualization**: Plot metrics to evaluate the model’s performance.

## Requirements
The following Python libraries are required:
- OpenCV (`cv2`)
- TensorFlow (`tensorflow`)
- NumPy
- Matplotlib
- OS
- Random
- Math
- Datetime

To install the dependencies, use:
```bash
pip install opencv-python tensorflow numpy matplotlib
```


## Functions
### `frames_extraction`
Extract frames from video files for dataset creation.

### `create_dataset`
Organize and preprocess data into a format suitable for model training.

### `create_LRCN_model`
Build an LRCN model leveraging TensorFlow/Keras to process sequential data.

### `plot_metric`
Generate plots for model evaluation metrics such as accuracy and loss.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ns-0437/Human-Activity-Recognition-in-Dark.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Human-Activity-Recognition-in-Dark
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook arid_HAR.ipynb
   ```
4. Run the cells sequentially to execute the entire workflow.

## Project Structure
```
/
|-- arid_HAR.ipynb   # Main notebook file
|-- data/            # Directory for storing video data
|-- models/          # Directory for saving trained models
|-- plots/           # Directory for storing metric visualizations
```

## Results
The project provides:

- Trained LRCN models capable of recognizing human activities from video sequences.
- Visualizations of training accuracy and loss to assess model performance.
