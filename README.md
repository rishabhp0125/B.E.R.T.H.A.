----------------------------------------------------------
| B.E.R.T.H.A. - v0.1 - Rishabh Prasad & Nicholas Scarpa |
----------------------------------------------------------

Our detection Code / Config files build upon YOLOv5's object detection software {github page - https://github.com/ultralytics/yolov5}
B.E.R.T.H.A. and the YOLOv5 framework was trained through the COCO database {more info at https://cocodataset.org/#home}

B.E.R.T.H.A. Information:

B.E.R.T.H.A runs off of YOLOv5s - uses a confidence tolerance of 40%
Models such as YOLOv5x improve performance, however, may not be compatible with microprocessors such as the Raspberry Pi 4B used in our project.

To try out B.E.R.T.H.A. enter a python venv and run "python detect.py --weights yolov5s.pt --source 0 --conf-thres 0.4"
If the code throws an unknown module error, please run "pip install -r requirements.txt"

For slower hardware, we reccomend modifying parameters such as iou-thres and max_det {default values are documented in code}

For more info on how B.E.R.T.H.A. was made, please see our devpost page, or our hackathon submission video

From our devpost submission:
https://devpost.com/software/b-e-r-t-h-a
