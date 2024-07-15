# innovative-monitoring-for-teleicu-patients-using-video-processing-and-deep-learning


<img src="https://github.com/user-attachments/assets/2cfee51e-6028-4015-8ae9-b49ca6483285" alt="image" width="200"/>


# Tele-ICU Implementation and Computer Vision Model Training

## Step 1: ICU Equipment Setup
- Completed the setup of all ICU equipment in the tele-ICU room.
- Installed high-resolution devices equipped with cameras to monitor patients 24/7.
- The tele-ICU concept involves one person monitoring patients remotely and notifying the doctor or nurse as needed.

## Problem Statement
- Assist patients in remote locations using tele-ICU.
- Utilize computer vision to identify patient conditions through video feeds from tele-ICU cameras, without relying on audio.

## Data Collection and Preparation
1. Watched a few YouTube videos, such as "ICU SEASON," and used these videos as datasets for the tele-ICU camera.
2. Downloaded the video and installed the necessary libraries.
3. Extracted frames from the video and stored them in a folder named `ICU_season_frames`.

## Model Training
1. Organized the extracted frames into three folders for training and validation purposes:
   - `train` (number of images: 1013)
   - `val` (number of images: 123)
   - `testset` (number of images: 62)
2. Categorized certain frames into four distinct groups: doctor, nurse, patient, and family member.
3. Converted the frames to images and annotated these images with bounding boxes using the "AnyLabeling" tool.
4. Trained a model based on YOLO model version V10.

## Model Validation
- Validated the results to identify the required classes.


