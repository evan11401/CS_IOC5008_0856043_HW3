# CS_IOC5008_0856043_HW3

## 1. Development environment
Python version : 3.7.4

Framework : Pytorch

## 2. How to run the code.
### (1)put the train image in data/custom/images

### (2)put the test images in data/custom/test

### (3) analysis the digitStruct.mat file.

Run data/custom/parsedata.py

It will make each test images one txt file for the ground-truth in data/custom/labels.

### (4)Spilt the train data using maketxt.py
It will store 90% data in data/custom/train.txt for train-set and 10% in data/custom/val.txt for validation-set.

### (5)Run train.py
Change the pretrained_weights to train from the pretrained network.

After train, it will create .pth file and we can do some test or predict the result.

### (6)detect
Run the detect.py, it will draw the predict result on the test images in data/custom/output

### (7)Print Json
Run printjson.py and it will create the result that dump into the json form in data/custom/0856043_.json
