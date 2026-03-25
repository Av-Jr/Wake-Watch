# VigilDrive: Driver Drowsiness Detection

## Description
VigilDrive is a real-time safety application designed to monitor driver alertness and prevent accidents caused by fatigue. The system uses computer vision to detect if a driver's eyes remain closed for an unsafe duration.

## Features
* **Real-time Monitoring**: Uses a live camera feed to track the driver's face and eyes.
* **Automated Detection**: Employs Haar Cascade classifiers for both frontal face and eye detection.
* **Visual Alerts**: Triggers a red "DROWSY" warning on the screen when potential sleep is detected.
* **Time-Based Logic**: Includes a configurable alert threshold, currently set to 2.0 seconds of continuous eye-closure.

## Prerequisites
* Python 3.x
* OpenCV (`opencv-python`)

## Installation
1.  **Clone the repository** to your local environment.
2.  **Install the required library**:
    ```bash
    pip install opencv-python
    ```

## Usage
Run the script using the following command:
```bash
python main.py
