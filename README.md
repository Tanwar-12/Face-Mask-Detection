# FACE MASK DETECTIONFace😷 {An Amazing Project}

### Overview : 
The purpose of this project is to create a Deep Learning model that identifies whether or not someone is wearing a mask. My model is based on YOLO's object detection algorithm, and I'm using the dataset from Roboflow website.

### Dataset : 
 https://public.roboflow.ai/object-detection/mask-wearing

**The dataset consists of two classes :**
- with_mask
- without_mask
![image](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/c13756bd-db6f-4ba6-a910-efc6adb88675)

  # Data Preparation:
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  ![train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)
## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open coco128.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 600 epochs .
* Visualise the training metrics with the help of tensorboard.

 ## Testing Images Using Test Data
![image](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/cee50f08-546b-47ba-aa9d-41e57ef44d07)
![download (12)](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/da459f43-b412-4883-8eae-9f63d2bcd5a1)

## Testing Video Demo:
Face mask detection is an object detection task that detects whether people are wearing masks or not in videos. This repo includes a demo for building a face mask detector using YOLOv5 model. 

  


https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/a5052014-e850-4dc3-9bd1-9733c520fff8

## Just follow☝️ me and Star⭐ my repository 
## Motivated and supported by the works of,
[Mr.Mukesh Pawar (Brother)].
