
# 	Demos Created using TensorFlow.JS    


## Facemesh-Camera.html :

[![Face-Mesh Demo](https://img.youtube.com/vi/8OIEeK09DVg/0.jpg)](https://www.youtube.com/watch?v=8OIEeK09DVg)

			Real-time Face Tracking using TensorFlow.js

			Takes live video stream from webcam and creates facemesh
			(facial feature-map) by capturing 468 facial landmark points

			To run using .mp4 video file, simply add
			<source src="VIDEO_PATH" type="video/mp4">
			tag inside <video> </video> in HTML

			and comment out live_webcam() function call..

			Link to TensorFlow.JS FaceMesh model:
			https://github.com/tensorflow/tfjs-models/tree/master/facemesh

## Body-Segment.html   :

[![Body-Segmentation Demo](https://img.youtube.com/vi/ryzB5qCP8KY/0.jpg)](https://www.youtube.com/watch?v=ryzB5qCP8KY)

			Body Segmentation using TensorFlow.JS Body-Pix model

			Takes live video stream from web camera, and runs
			segmentation using Body-Pix model from TensorFlow.JS

			Link to TensorFlow.JS Body-Pix model :

			https://github.com/tensorflow/tfjs-models/tree/master/body-pix

## Video-Tagging.html  :

[![Video-Tagging Demo](https://img.youtube.com/vi/2U7XreZlw_U/0.jpg)](https://www.youtube.com/watch?v=2U7XreZlw_U)

			Identifies animal species in Wild-Life documentary films using
			Mobile-Net Image Classification model in TensorFlow.JS

			Link to TensorFlow.JS Mobile-Net model :

			https://github.com/tensorflow/tfjs-models/tree/master/mobilenet

			Sample video : wild-life.mp4

## Object-Detection.html :

[![Object Detection Demo](https://img.youtube.com/vi/MrTGiH3UEoQ/0.jpg)](https://www.youtube.com/watch?v=MrTGiH3UEoQ)

			Marks Bounding Boxes around the Objects detected in the video using
			TensorFlow.JS COCO-SSD model..

			Link to TensorFlow.JS COCO-SSD model :

			https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd


## Activity-Recognition.html :
[![Activity Recognition Demo](https://img.youtube.com/vi/7QB1AgsR-qc/0.jpg)](https://www.youtube.com/watch?v=7QB1AgsR-qc)

			Builds a KNN Classifier for Sports Activity Recognition using
			Transfer Learning on a pre-trained model Mobile-Net

			Link to KNN Classifier in TensorFlow.JS :

			https://github.com/tensorflow/tfjs-models/tree/master/knn-classifier

			Activity Recognition can be performed in 3 simple steps:

			1. Compile training video which demonstrates various sports activities
			that you want to capture automatically using Machine Learning

			2. For each activity, capture few screenshots from the training video
			and tag them manually to train the knn-classifier

			3. Run predictions using the knn-classifier

## Green-Screen.html :

[![Chroma-Key Demo](https://img.youtube.com/vi/ZUDdECVFBOE/0.jpg)](https://www.youtube.com/watch?v=ZUDdECVFBOE)

			Extracts person from an input video stream using Body-Pix model in
			TensorFlow.JS and replaces the video backdrop

			Sample background images are provided in this directory 'backdrop-k.jpg'.

			Link to TensorFlow.JS Body-Pix model:

			https://github.com/tensorflow/tfjs-models/tree/master/body-pix

## Gesture-Recognition.html :

[![Hand-Tracking Demo](https://img.youtube.com/vi/CTGRbU9-P6U/0.jpg)](https://www.youtube.com/watch?v=CTGRbU9-P6U)

			Using Hand-Gestures to move objects in Virtual / Augmented Worlds

			Hand Positions are tracked using Hand-Pose model in TensorFlow.JS

			Link to Hand-Pose model:

			https://github.com/tensorflow/tfjs-models/tree/master/handpose

			More gesture-controlled features to Pause, Browse, Scroll, Zoom Media Stream to be added..

## Sound-Box.html :

[![Sound-Box Demo](https://img.youtube.com/vi/REbq8Fq0BIw/0.jpg)](https://www.youtube.com/watch?v=REbq8Fq0BIw)

			Music Generation using Hand-Gestures

			Generates sounds using Tone.JS Java Script library, 
			based on Hand Positions captured by TensorFlow.JS Hand-Pose model..

			Each sound-box at (x, y) produces a sound with frequency f(x,y)

			Link to Tone.JS library:

			https://tonejs.github.io

Tech Stack: TensorFlow.JS, JavaScript, HTML5, Mobile-Net, Knn-Classifier, Coco-SSD, Tone.JS
