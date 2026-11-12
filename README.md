# Acne Detection Using Deep Learning

## Overview

This project uses **YOLOv8n** to detect acne in facial images. The model is trained using an acne image dataset obtained from Roboflow.

## Dataset

- **Dataset:** [Acne YOLO – Roboflow](https://universe.roboflow.com/ance-yolo/acne-yolo/dataset/13)
- **Version:** 13
- **Classes:** 1 (`acne`)
- **License:** CC BY 4.0

## Technologies Used

- Python
- YOLOv8n (Ultralytics)
- Roboflow
- Jupyter Notebook

## Model Training

Two training experiments are included:

- `main.ipynb` – 50 epochs
- `100Epoch.ipynb` – 100 epochs

Both experiments use an image size of 640 and a batch size of 16.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install ultralytics jupyter
   ```

3. Download the dataset from the Roboflow link above.
4. Update the dataset paths in `data.yaml` if necessary.
5. Open either notebook using Jupyter Notebook.
6. Run the cells to train the model and test image detection.

## Repository Structure

- `main.ipynb` – Model training and inference (50 epochs).
- `100Epoch.ipynb` – Model training and inference (100 epochs).
- `data.yaml` – Dataset configuration.
- `yolov8n.pt` – YOLOv8n pretrained weights.

## Note

Dataset paths may need to be adjusted depending on your local setup.
