# MP-LiCounter

UZH Master Project June 2021 - Feb 2022

Jiaqi Zhang (20-740-213), Chuqiao Yan (20-740-619)

LiCounter: A method for LiDAR Based Counting Method 

## Files
### Contained in Train Yolov3 Model.zip
Due to the storage space, the training files has beed saved locally

+ Images can be downloaded here: https://drive.google.com/drive/folders/163ZHOsOfUeV_i58GCSPZEvy_OeKVVeTg?usp=sharing

+ Training process of 9 models: yolov3_day_mix, yolov3_day_night, yolov3_daytime, yolov3_mix_day, yolov3_mix_night, yolov3_mix, yolov3_night_day, yolov3_night_mix, yolov3_night

+ Files used during training: generate_test.py, generate_train.py, obj.data, obj.names, yolov3_custom.cfg

+ color_img_1632124522.891653.jpg is the image used to test detector

### Contained in DeepSort.zip
This file can be used to run Deep Sort tracking. Download and run this in command line:

conda activate tracker-gpu

python object_tracker1.py --output ./data/video/results.avi --weights ./weights/yolov3-custom.tf --num_classes 1 --classes ./data/labels/obj.names


# Reference
https://github.com/theAIGuysCode/YOLOv3-Cloud-Tutoria
