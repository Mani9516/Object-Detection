# YOLO Object Detection with Streamlit
This Streamlit app allows users to perform object detection on both images and videos using YOLO (You Only Look Once). The app also features a dynamic background video, a progress bar for processing, and a user-friendly interface.

Features
Upload Media: Single uploader for both images and videos.
YOLO Detection: Object detection with bounding boxes and class labels.
Progress Bar: Indicates processing progress for videos.
Interactive Interface: Intuitive UI for seamless media processing.
Installation
Clone the Repository:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install Requirements:

pip install -r requirements.txt
Download YOLO Files:

yolov3.weights: Pre-trained weights file required for object detection. Download it from the YOLO website.
yolov3.cfg: Configuration file defining the YOLOv3 network architecture.
coco.names: A list of 80 object categories supported by YOLO.
Run the App:

streamlit run app.py
Usage
Upload Media:

Drag and drop an image or video into the uploader.
Processing:

The app will detect objects in images/videos and display the results with bounding boxes and labels.
Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

Acknowledgments
YOLOv3: Pre-trained model by Joseph Redmon and Ali Farhadi.
Streamlit: Framework for building interactive Python apps.
