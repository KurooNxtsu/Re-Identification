<<<<<<< HEAD
# Re-Identification
This repository contains the implementation for a person re-identification (Re-ID) pipeline using state-of-the-art object tracking methods like StrongSORT, BoT-SORT, and DeepSORT with a YOLOv8 object detector. The pipeline supports integration with OSNet for appearance-based feature embedding and traditional Re-ID.
Install Required Packages
Download all necessary dependencies using the requirements.txt file:

Before running the notebook or scripts, make sure to install all required dependencies using pip install -r requirements.txt. Many file paths used in this project are currently hardcoded for local testing purposes, so you must update them to match your own environment. Specifically, you should change the YOLO model path (best.pt), ReID model path (osnet_x1_0_msmt17.pt), input video path (e.g., input_video.mp4), and output video or result directory path. Look for variables in the code like YOLO_MODEL_PATH, REID_MODEL_PATH, VIDEO_INPUT, and OUTPUT_VIDEO_PATH, and update them according to your local setup before execution.
=======
Before running any of the code snippets or notebooks (assignment.ipynb), please ensure the following:
Install Required Packages,
Download all necessary dependencies using the requirements.txt file: pip install -r requirements.txt
Update File Paths
Many paths used in the code are currently hardcoded for local testing.
Before running the notebook or scripts, please update the following paths to match your environment:
YOLO model path (best.pt)
ReID model path (osnet_x1_0_msmt17.pt)
Video input path (e.g., 15sec_input_720p.mp4)
Output directories or result video path.
Make sure to adjust these according to your directory structure before executing the code.
>>>>>>> 8bea622 (Initial commit for re-identification problem)
