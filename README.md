
##### 	Demos Created using TensorFlow.JS    #####


Facemesh-Camera.html :

			Real-time Face Tracking using TensorFlow.js


			Takes live video stream from webcam and creates facemesh
			(facial feature-map) by capturing 468 facial landmark points

			To run using .mp4 video file, simply add 
			<source src="VIDEO_PATH" type="video/mp4"> 
			tag inside <video> </video> in HTML

			and comment out live_webcam() function call..

			Link to TensorFlow.JS FaceMesh model:
			https://github.com/tensorflow/tfjs-models/tree/master/facemesh

Body-Segment.html   :

			Body Segmentation using TensorFlow.JS Body-Pix model

			Takes live video stream from web camera, and runs
			segmentation using Body-Pix model from TensorFlow.JS

			Link to TensorFlow.JS Body-Pix model :

			https://github.com/tensorflow/tfjs-models/tree/master/body-pix

Video-Tagging.html  :

			Identifies animal species in Wild-Life documentary films using
			Mobile-Net Image Classification model in TensorFlow.JS

			Link to TensorFlow.JS Mobile-Net model :

			https://github.com/tensorflow/tfjs-models/tree/master/mobilenet

			Sample video : wild-life.mp4

Object-Detection.html :

			Marks Bounding Boxes around the Objects detected in the video using
			TensorFlow.JS COCO-SSD model..

			Link to TensorFlow.JS COCO-SSD model :

			https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd


Activity-Recognition.html :

			Recognizes Sports Activities in the video using Transfer Learning 

			Uses Pre-trained model Mobile-Net to extract features which are passed 
			to the K-Nearest Neighbor Classifier for predictions

			Link to KNN Classifier in TensorFlow.JS :

			https://github.com/tensorflow/tfjs-models/tree/master/knn-classifier

			Activity Recognition can be performed in 3 simple steps:

			1. Capture screenshot from video

			2. Label few examples to train the classifier

			3. Capture few test images and run prediction to recognize the activity

			Presently, following sports activities are supported:

			Swimming, Cycling, Boxing, Surfing, Figure Skating, Horse Riding

			Simply load any video that contains the above activities in HTML, tag
			few screenshots (~10-15 per class) and run predictions..


Tech Stack: TensorFlow.JS, JavaScript, HTML5, Mobile-Net, Knn-Classifier, Coco-SSD
