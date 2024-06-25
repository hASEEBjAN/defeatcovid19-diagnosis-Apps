# defeatcovid19-diagnosis-Apps
This repository contains prototypes of a mobile app, a web app, a Flask application, and a Jupyter notebook for training models on a Covid-19 dataset.

## AI_Training_for_covid19.ipynb
This Jupyter notebook includes scripts written to train models on the Covid-19 dataset. The trained models will be used in the applications mentioned below.

## COVID19_X_RAY_SCANNER_FLUTTER
This is a Flutter app that uses TensorFlow Lite for image classification. The model trained using the Jupyter notebook will be implemented in this app to classify X-ray images as either positive or negative for Covid-19.

## COVID19_X_RAY_SCANNER2_FLUTTER
This is a Flutter app that uses TensorFlow Lite for object detection. The model trained using the Jupyter notebook will be implemented in this app to detect symbols in X-ray images related to Covid-19.

## COVID19_DIAGNOSIS_FLASK
This is a Flask web application that provides an interface for uploading X-ray images and displays the diagnosis results using the models trained in the Jupyter notebook.

Multiple apps are being developed to determine which performs better for further development.
