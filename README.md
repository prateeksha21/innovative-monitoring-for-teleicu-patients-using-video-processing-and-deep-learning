# innovative-monitoring-for-teleicu-patients-using-video-processing-and-deep-learning


![image](https://github.com/user-attachments/assets/2cfee51e-6028-4015-8ae9-b49ca6483285)



The first step I took was completing the setup of all ICU equipment in the tele-ICU room.
These are high-resolution devices equipped with cameras to monitor patients 24/7. 
The concept of the tele-ICU involves one person monitoring the patients remotely and notifying the doctor or nurse as needed.
The problem statement mainly involves assisting patients in remote locations. 
The goal is to utilize computer vision to identify patient conditions through video feeds from the tele-ICU cameras, without relying on audio.
To begin,I watched a few YouTube videos, such as "ICU SEASON," and used these videos as data sets for the tele-ICU camera. 
I downloaded the video, installed the necessary libraries, and extracted frames from the video, storing them in a folder named "ICU_season_frames."
After extracting the frames, I trained a model and organized the frames into folders named "train"(no.of images 1013), "val"(no.of images 123) and testset(no.of images 62) for training and validation purposes.
 I also categorized certain frames into three distinct groups: doctor, nurse, patient, and family member.
Converted the frames to images and those images were annotated as   bounding box using "AnyLabelling" tool.
Trained a model based on yolo model version V10 then  validated the results
The results were validated to identify the required classes 

