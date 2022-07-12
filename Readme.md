# Hand Gesture Recognition - Video Classification
 Hand Gesture Recognition using CNN+LSTM/3D CNN

## Problem Statement
- To develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote
- The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
   1. Thumbs up:  Increase the volume
   2. Thumbs down: Decrease the volume
   3. Left swipe: 'Jump' backwards 10 seconds
   4. Right swipe: 'Jump' forward 10 seconds  
   5. Stop: Pause the movie
 
## Experiments Performed

### CNN+LSTM

1. **four layers of Conv2d + one layer of LSTM**

   | Best Val Acc  | Best Val Loss  |
   | ------------- | -------------- | 
   | 74.00%        | 0.8338         |

   - model overfitting on the train data

2. **four layers of Conv2d + one layer of LSTM - adding droput layer**  

   | Best Val Acc  | Best Val Loss  |
   | ------------- | -------------- |
   | 74.00%        | 0.768570       |

   - need to increase the dropout layer percent as the model is still overfitting on the train data
   - Hyper-parameter tuning required

### 3D CNN

1. **two layers of Conv3d**
   (experimenting with the model)

   
## References

- [Human Activity Recognition using TensorFlow](https://youtu.be/QmtSkq3DYko)
- https://keras.io/examples/vision/3D_image_classification/
- https://github.com/0aqz0/SLR
- https://github.com/anujshah1003/custom_data_generator/tree/master/activity_recognition
- https://github.com/HHTseng/video-classification
