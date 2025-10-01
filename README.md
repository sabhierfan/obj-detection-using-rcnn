# Object Detection using Detectron2

This project demonstrates object detection on an image using the Detectron2 library in a Google Colab notebook.

## Project Description

The notebook performs the following steps:

1.  Installs necessary libraries, including Detectron2 and pycocotools.
2.  Imports required modules for image processing and object detection.
3.  Downloads and extracts the COCO 2017 validation dataset (for demonstration purposes, though the model used is pre-trained).
4.  Loads a pre-trained Faster R-CNN model from the Detectron2 model zoo.
5.  Loads an image and performs object detection using the loaded model.
6.  Visualizes the detection results on the image.
7.  Includes a function to calculate Intersection over Union (IoU) (though not used in the main execution flow).
8.  Measures and displays the inference time and speed of the model.

## How to Use

1.  Open the Google Colab notebook using the link below.
2.  Run all the cells in the notebook.
3.  Replace the placeholder image path in the cell loading the image with the path to your desired image file.
4.  (Optional) Modify the confidence threshold or other model parameters as needed.
5.  Run the cells again to see the object detection results on your image.

## Google Colab Notebook

[[Link to  Google Colab notebook here](https://colab.research.google.com/drive/1JkEm3n0RtLWN01jY6zF9kb7hSvdll6U0?usp=sharing)]



## Requirements

The notebook automatically installs the required libraries.

## File Structure

The project consists of a single Google Colab notebook. The downloaded dataset and annotations will be placed in the Colab environment during execution.

## License

[MIT License]
