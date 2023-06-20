# Fall-Detection

Clone yolov5 by Ultralytics repo:
```
git clone https://github.com/ultralytics/yolov5.git
```
Download fall detection model 

Clone this repo and move all files and downloaded model into cloned yolov5 repo

CD into directory and create and activate virtual environment:
```
python -m venv .venv
.\.venv\Scripts\activate
```

Install requirements:
```
pip -m install --upgrade pip
pip install -r requirements.txt
```

Run inference:
```
python fall_detection.py --weights best.pt --conf-thres 0.8 --source fall5.mp4
```
