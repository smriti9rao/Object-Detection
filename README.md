# Video Object Detection

This repository contains a script to read frames from a video, detect objects in each frame using YOLOv5, and save the cropped objects into a folder.

## Requirements

- Python 3.x
- OpenCV
- PyTorch
- PIL
- YOLOv5

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/smriti9rao/video-object-detection.git
    cd video-object-detection
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Update the `video_path` in `detect_objects.py` to point to the video file.

4. Run the script:
    ```bash
    python detect_objects.py
    ```

The cropped objects will be saved in the `cropped_objects` folder.
