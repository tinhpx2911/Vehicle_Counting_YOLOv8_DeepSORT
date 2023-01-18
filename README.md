<H1 align="center">
YOLOv8 Vehicles Counting with DeepSORT Tracking</H1>

## Steps to run Code

- Clone the repository
```
git clone https://github.com/tinhpx2911/Vehicles_Counting_YOLOv8_DeepSORT.git
```
- Goto the cloned folder.
```
cd Vehicles_Counting_YOLOv8_DeepSORT
```
- Install the requirements
```
pip install -r requirements.txt
pip install -r requirements_gpu.txt
```

- Goto the Directory.
```
cd ultralytics/yolo/v8/detect
```

- Run the code with mentioned command below.

```
python predict.py model=yolov8x.pt source="Freeway.mp4" show=True
```

### RESULTS


#### Vehicles Detection, Tracking and Counting

https://user-images.githubusercontent.com/100455964/213140761-7fcc53ab-6279-4c38-acf9-223325f14877.mp4

