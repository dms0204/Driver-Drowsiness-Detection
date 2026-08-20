# Driver-Drowsiness-Detection
A small deep learning project for detecting visual signs of driver drowsiness using YOLO11n.
This project uses a YOLO11n object detection model to detect the driver's eye and mouth states from images and videos.

The model is trained to recognize four classes:
- eye_open
- eye_closed
- mouth_open
- mouth_closed

The detected states are then used to identify simple visual signs of drowsiness, such as prolonged eye closure or repeated mouth opening.

Our pipeline
Dataset → Annotation → YOLO11n Training → Evaluation → Detection → Drowsiness Classification

1. Prepare and annotate the dataset
2. Train a YOLO11n object detection model
3. Evaluate model performance using precision, recall and mAP
4. Test the trained model on images and videos
5. Analyze detected eye and mouth states
6. Determine whether the driver shows signs of drowsiness