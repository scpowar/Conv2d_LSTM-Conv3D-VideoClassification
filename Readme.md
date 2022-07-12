# Hand Gesture Recognition
 Hand Gesture Recognition using CNN+LSTM/3D CNN

## Problem Statement
- To develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote
- The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
   - Thumbs up:  Increase the volume
   - Thumbs down: Decrease the volume
   - Left swipe: 'Jump' backwards 10 seconds
   - Right swipe: 'Jump' forward 10 seconds  
   - Stop: Pause the movie
 
## Experiments Performed

### CNN+LSTM

1. **four layers of Conv2d + one layer of LSTM**

   | Best Val Acc  | Best Val Loss  |
   | ------------- | -------------- |
   | 82.08%        | 0.734426       |

2. **four layers of Conv2d + one layer of LSTM - adding droput layer**  

   | Best Val Acc  | Best Val Loss  |
   | ------------- | -------------- |
   | 74.00%        | 0.768570       |

### 3D CNN

1. **three layers of Conv3d**
(coding is complete; model evaluation pending)

   
## References

- [Human Activity Recognition using TensorFlow](https://youtu.be/QmtSkq3DYko)
- https://keras.io/examples/vision/3D_image_classification/
- https://github.com/0aqz0/SLR
- https://github.com/anujshah1003/custom_data_generator/tree/master/activity_recognition
- https://github.com/HHTseng/video-classification
