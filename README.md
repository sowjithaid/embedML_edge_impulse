# embedML_edge_impulse
Embedded Machine Learning Intro

Create virtual environment in Mac:
[sudo pip install virtualenv](https://mnzel.medium.com/how-to-activate-python-venv-on-a-mac-a8fa1c3cb511)

Edge Impulse:
https://docs.edgeimpulse.com/docs/development-platforms/officially-supported-cpu-gpu-targets/edge-impulse-linux-macos

Data Aquisition - Balanced set (equal data in all classes)
Split data set to Training and Test set (80-20)

Create Impulse -> Feature extraction (i/p) + Classifier (Model) 
  Classifier -> select layers and start traning
Check Accuracy and Loss and Performance Matrix

Download the CLassifier data (it gives all the computational info. of Neural Metwork Layers) and view in netron.app
  Notice: Input and output data is quantized to convert to 8 bit integer to save memory.

Test Model on web (Test set)
Live Classification - collect data and see predictions on web
Real Time Classification - Deploy model to phone + collect data and see prediction in real time (2 threads for data collection and data prediction-model stuff)

Anamoly Detection (Detects data not belonging to any of the featured class):
Add Anamoly detection block to Impulse design

