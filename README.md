# TensorFlow.js Example: Transfer Learning to play Pacman via the Webcam

**This is a unmodified demo of tfjs-examples/webcam-transfer-learning/ repo**
**to demonstrate a regression bug that causes Safari iOS not to be able to predict moves**

I only added a console.log() on index.js:121 to show where it starts to show loss "NaN" after the first batch)

The public demo WORKS on Safari iOS as it seems to be the 2019-06-12 version
https://storage.googleapis.com/tfjs-examples/webcam-transfer-learning/dist/index.html
--> https://github.com/tensorflow/tfjs-examples/tree/fc8646fa87de990a2fc0bab9d1268731186d9f04

But the actual code at https://github.com/tensorflow/tfjs-examples (2020-04-16) does NOT work on Safari iOS
(it still works well on computer based browsers).