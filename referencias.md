- Official course from google on Machine Learning for Web Developers (Web ML): https://youtube.com/playlist?list=PLOU2XLYxmsILr3HQpqjLAUkIPa5EaZiui
- Projects made with TensorFlow: https://youtube.com/playlist?list=PLQY2H8rRoyvzSZZuF0qJpoJxZR1NgzcZw
- Training ML on Google: https://teachablemachine.withgoogle.com/

## Class 01

- Calculation Code: https://github.com/monaca-samples/blink-to-text/blob/f3d578ff641298913833b04e98e854bf1cfe38e1/src/js/blinkPrediction.js
- Dependencies of the worker.js

```js
import "https://unpkg.com/@tensorflow/tfjs-core@2.4.0/dist/tf-core.js";
import "https://unpkg.com/@tensorflow/tfjs-converter@2.4.0/dist/tf-converter.js";
import "https://unpkg.com/@tensorflow/tfjs-backend-webgl@2.4.0/dist/tf-backend-webgl.js";
import "https://unpkg.com/@tensorflow-models/face-landmarks-detection@0.0.1/dist/face-landmarks-detection.js";
```

- Database used: https://www.kaggle.com/code/vikassingh1996/netflix-movies-and-shows-plotly-recommender-sys/data
- Convert video to canvas: https://stackoverflow.com/questions/64249599/how-to-run-handpose-tfjs-model-in-web-worker
- tensorflow blog on iris detection: https://blog.tensorflow.org/2020/11/iris-landmark-tracking-in-browser-with-MediaPipe-and-TensorFlowJS.html
- tensorflow lib: face-landmarks-detection: https://github.com/tensorflow/tfjs-models/blob/master/face-landmarks-detection
- workers api: https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API/Using_web_workers
- module workers: https://web.dev/module-workers/
- check compatibility: caniuse.com
- another example of blink detection: https://selvamsubbiah.com/mediapipe-iris-detection-in-tensorflow-js/
- identifying morse code with eye detection: https://medium.com/the-web-tub/recognising-eye-blinking-with-tensorflow-js-3c02b738850d
- layout used: https://codepen.io/Gunnarhawk/pen/vYJEwoM
- Explanation of why webgl, cpu, webassembly: https://youtu.be/3ive-w7oUis?t=333

## Class 02

- Gestures file to copy: https://github.com/andypotato/rock-paper-scissors/blob/54add341dbe83287c8ede69fbb006149a8145dd9/src/js/Gestures.js
- Imports from the archive handGestureFactory:

```js
import "https://cdn.jsdelivr.net/npm/@tensorflow/tfjs-core@4.2.0/dist/tf-core.min.js";
import "https://unpkg.com/@tensorflow/tfjs-backend-webgl@3.7.0/dist/tf-backend-webgl.min.js";
import "https://cdn.jsdelivr.net/npm/@mediapipe/hands@0.4.1646424915/hands.min.js";
import "https://cdn.jsdelivr.net/npm/@tensorflow-models/hand-pose-detection@2.0.0/dist/hand-pose-detection.min.js";
import "https://cdn.jsdelivr.net/npm/fingerpose@0.1.0/dist/fingerpose.min.js";
```

- Problem I encountered when using webworker in hands.js: https://github.com/tensorflow/tfjs/issues/7380
- PR open in fingerpose: https://github.com/andypotato/fingerpose/pull/25
- Fingerpose: https://github.com/ErickWendel/fingerpose
- Jokenpo: https://github.com/andypotato/rock-paper-scissors
- TensorFlow HandPoseDetection Diagram: https://github.com/tensorflow/tfjs-models/tree/master/hand-pose-detection#keypoint-diagram

## Class 03

- Solar Hands Project: https://github.com/liady/solar-hands
- Tensorflow API finger indices: https://github.com/tensorflow/tfjs-models/tree/a345f0c58522af25d80153ec27c6e999e45fdd42/hand-pose-detection#keypoint-diagram
- elementFromPoint API: https://developer.mozilla.org/en-US/docs/Web/API/Document/elementFromPoint
