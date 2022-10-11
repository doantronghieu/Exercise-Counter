# PROJECT

## Main Functions

- Pose Detection (Body landmarks) using BlazeFace model ([MediaPipe Library](https://google.github.io/mediapipe/)).
- Action Recognition using LSTM neural network.
- Exercise counter application:
  - Step 01: Detect action using LSTM. Input feature: All body landmark values extracted from sequence of video frames.
  - Step 02: Once the action is detected surely (in the action detection phase). Start the count phase. Once the counter reached its maximum value (maximum reps set by default), the counter is stop, the system will swich to detection phase.

## Demo
https://user-images.githubusercontent.com/89921814/194993677-30251afa-ff9c-44bc-9fde-19547d005abc.mp4
