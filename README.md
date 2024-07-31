# Intrusion Detection System

## Overview

This project implements an intrusion detection system using a YOLO model to detect persons and OpenCV to handle video processing and region drawing. The system alerts when a person enters specified regions on a video frame and logs the details in a CSV file.

## Features

- Dynamic region drawing on video frames
- Person detection using a pretrained YOLO model
- Intrusion alert with sound and visual message
- Logs intrusion details in a CSV file

## Requirements

- Python 3.x
- OpenCV
- Ultralyics YOLO
- Numpy
- Pydub

## Installation
```bash
pip install ultralytics 
pip install pydub
sudo apt update
sudo apt install ffmpeg

