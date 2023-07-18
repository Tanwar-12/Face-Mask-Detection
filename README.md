# FACE MASK DETECTION
To build a system for detectiong if an individual is wearing a mask in a given image.

## DATA OVERVIEW & COLLECTION:
The Mask Wearing dataset is an object detection dataset of individuals wearing various types of masks and those without masks. The images were originally collected by Cheng Hsun Teng from Eden Social Welfare Foundation, Taiwan and relabeled by the Roboflow team.

* Download from: https://public.roboflow.ai/object-detection/mask-wearing.
* Dataset contain total 149 images into two classes i.e Mask & Without Mask.
* Example image (some with masks, some without):
 ![image](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/6ba87ec1-e249-4126-8662-2cd14403f0c4)

  


## DATA PREPRATION:
* Prepare folder structure that can be accept by YoloV5.
* Total 105 images for training and 29 images for validation present in 2 classes.
* Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.

## STEPS TO USE YOLOV5
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights

## STEPS BEFORE TRAINING CUSTOM DATASET:
1. Go to yolov5/data/
2. Open coco128.yaml
3. Edit the following inside it:

     A. Training and Validation file path

     B. Number of classes and Class names.

## TRAINING YOLOV5 MODEL
* Set images size 640 with batch of 8
* Train model around 600 epochs but Stopping training at 440. 
* Visualise the training metrics with the help of tensorboard

## TESTING IMAGES USING TEST DATA

![download (12)](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/62be98ad-ef53-4287-8f07-5675f471a90e)
![download (13)](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/31b2ccba-6e28-48c1-bd68-867e3416c9e5)

## TESTING LOW QUALITY VIDEO DEMO

https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/e1a766a3-d46e-40dd-a4e5-a55400653160





## CHALLENGES FACED:
*	challenge faced in bounding boxes creation
*	Assign the same no for all classes
*	Made mistake in yolov5 folder structure
*	Take lots of time to create bounding boxes

## WHAT WE LEARN:
*	Understand the YoloV5 folder structure as well as learn label-IMG tool.
*	Learn Pytorch library.
