
# 	Demos Created using TensorFlow.JS    


## Facemesh-Camera.html :

<video width=640 height=480> <source src="https://www.youtube.com/watch?v=8OIEeK09DVg" type="video/mp4"> 
</source> </video>

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

			Body Segmentation using TensorFlow.JS Body-Pix model

			Takes live video stream from web camera, and runs
			segmentation using Body-Pix model from TensorFlow.JS

			Link to TensorFlow.JS Body-Pix model :

			https://github.com/tensorflow/tfjs-models/tree/master/body-pix

## Video-Tagging.html  :

			Identifies animal species in Wild-Life documentary films using
			Mobile-Net Image Classification model in TensorFlow.JS

			Link to TensorFlow.JS Mobile-Net model :

			https://github.com/tensorflow/tfjs-models/tree/master/mobilenet

			Sample video : wild-life.mp4

## Object-Detection.html :

			Marks Bounding Boxes around the Objects detected in the video using
			TensorFlow.JS COCO-SSD model..

			Link to TensorFlow.JS COCO-SSD model :

			https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd


## Activity-Recognition.html :

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

			Extracts person from an input video stream using Body-Pix model in 
			TensorFlow.JS and replaces the video backdrop

			Sample background images are provided in this directory 'backdrop-k.jpg'.

			Link to TensorFlow.JS Body-Pix model:

			https://github.com/tensorflow/tfjs-models/tree/master/body-pix

Tech Stack: TensorFlow.JS, JavaScript, HTML5, Mobile-Net, Knn-Classifier, Coco-SSD
