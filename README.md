# Project Introduction

This project explores the use of Mask R-CNN for pedestrian detection in smart city applications. Pedestrian detection plays a crucial role in various smart city initiatives, including:

1.Traffic management: Identifying pedestrians to optimize traffic light timing and improve pedestrian safety at crosswalks.
2.Crowd monitoring: Monitoring crowd density in public areas to prevent overcrowding and ensure public safety.
3.Urban analytics: Analyzing pedestrian activity patterns to inform urban planning and resource allocation decisions.

I have built pedestrian detection using Faster R-CNN which aims for self-driving car before, now I use Mask R-CNN, a popular object detection algorithm, by predicting not only bounding boxes but also instance segmentation masks around pedestrians. These masks provide more detailed information about, enhancing their usefulness in smart city applications.

# Benefits of Mask R-CNN: Mask R-CNN addresses this limitation by generating instance segmentation masks. This enables:
A.Determining pedestrian orientation (facing forward, backward)
B.Understanding potential movements based on body posture
C.Analyzing crowd density more effectively

# Approach
-Dataset Selection: I use PennFudanPedestrian dataset.
-Data Preprocessing: Apply necessary preprocessing techniques using mask R-CNN Resnet 50 to the dataset images and annotations to enhance model performance. 
-Model Training: Train a Mask R-CNN model on the prepared dataset using 100 epochs and two batch size. 
-Evaluation: Evaluate the trained model's performance on a separate validation dataset using metrics Average Precision for detection and IoU for segmentation.
-Application Exploration: Using a random image from Google to assess how well my model can accurately perform object detection, segmentation, and counting tasks.
