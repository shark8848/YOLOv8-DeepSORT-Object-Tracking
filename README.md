<H1 align="center">
YOLOv8 Object Detection with DeepSORT Tracking(ID + Trails) </H1>

## Google Colab File Link (A Single Click Solution)
The google colab file link for yolov8 object detection and tracking is provided below, you can check the implementation in Google Colab, and its a single click implementation, you just need to select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1U6cnTQ0JwCg4kdHxYSl2NAhU4wK18oAu?usp=sharing)

## Object Detection and Tracking (ID + Trails)  using YOLOv8 on Custom Data
## Google Colab File Link (A Single Click Solution)
[`Google Colab File`](https://colab.research.google.com/drive/1dEpI2k3m1i0vbvB4bNqPRQUO0gSBTz25?usp=sharing)

## YOLOv8 Segmentation with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/MuhammadMoinFaisal/YOLOv8_Segmentation_DeepSORT_Object_Tracking.git)

## Steps to run Code

- Clone the repository
```
git clone https://github.com/shark8848/YOLOv8-DeepSORT-Object-Tracking.git
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```
- Run the code with mentioned command below.

- For yolov8 object detection + Tracking
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```
- For yolov8 object detection + Tracking + Vehicle Counting
```
python predict_v2.py model=yolov8l.pt source="test3.mp4" show=True
```

### RESULTS

#### Vehicles Detection, Tracking and Counting 
![](./figure/figure1.png)

#### Vehicles Detection, Tracking and Counting

![](./figure/figure3.png)

### Watch the Complete Step by Step Explanation

- Video Tutorial Link  [`YouTube Link`](https://www.youtube.com/watch?v=9jRRZ-WL698)


[![Watch the Complete Tutorial for the Step by Step Explanation](https://img.youtube.com/vi/9jRRZ-WL698/0.jpg)]([https://www.youtube.com/watch?v=StTqXEQ2l-Y](https://www.youtube.com/watch?v=9jRRZ-WL698))

## Bug Fixes
Fixed DeepSORT compatibility with PyTorch 2.6+:
Resolved runtime errors caused by API changes in PyTorch 2.6, ensuring stable object tracking with the latest PyTorch versions.
## Bug identified by:[@shark8848](https://github.com/shark8848)
<a href="https://github.com/shark8848">
  <img src="https://github.com/shark8848.png?size=100" width="100" style="border-radius: 50%;" alt="头像">
</a>
