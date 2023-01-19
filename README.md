## Info: 
This repo provides a pipeline to train a cervix detector to be able to detect the cervix from images.

## Author: Syed Rakin Ahmed

## Usage

### 1. Clone this repo app
```
git clone https://github.com/rknahmed0/cervix_detector.git cervix_detector
```
### 2. Follow instructions as included in the README.md of the yolov5 directory to setup the yolov5 detector. YOLOv5 pipeline is cloned from https://github.com/ultralytics/yolov5/ and modified to suit retraining for cervix images.

### 3. Curate dataset, retrain the yolov5 detector on images of the cervix, and export to TFLite using the notebook provided in training_notebooks (change relevant paths as needed)

For questions specific to yolov5, please ask in https://github.com/ultralytics/yolov5/pull/1127

This repo already provides V1 of the trained model file in trained_models/V1 as both .pt (train_100ep_yolov5s_5study_liger_80_10_10.pt) and .tflite files (20221116-5-320-int8.tflite), as well as the notebook utilized to train this model in training_notebooks/V1