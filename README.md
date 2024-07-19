# YOLO Pepsi-CocaCola Detection Pipeline (VideoVerse Assignment)
This repository contains the code for the YOLO Pepsi-CocaCola Detection Pipeline. The pipeline is implemented using the YOLOv4 object detection model(Ultralytics). The pipeline is implemented in Python using the AV, OpenCV and Ultralytics libraries. The pipeline is capable of detecting Pepsi and CocaCola Logos in a video stream real-time and drawing bounding boxes around them= and returrn jsondata with the frames when each oft the logo was detected

## Demo
<img src="./demo.gif" width="1200" alt="Demo">

## Pepsi_Test
This folder uses a labelled dataset to test for pepsi logos in the video stream.

## CocaCola_Test
This folder uses a labelled dataset to test for coca cola logos in the video stream.

## Setup
1. Clone the repository.
2. Run a ipynb kernal with preferably GPU support and Python 12.
3. Run the code cells in the notebook to install the required libraries and run the pipeline.
4. if there is a numpyt version compatibility issue try `pip install numpy<2`.

## The specifics details are mentioned in the approach document
