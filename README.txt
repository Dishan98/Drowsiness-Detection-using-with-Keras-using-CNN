Drowsiness Detection using with Keras using Convolutional Neural Networks (CNN).

To run the application, open the "drowsiness detetction.py" in a python ide and run the program.

If above option doesn't work, first run the "model.py" to train the program. Then run the "drowsiness detection.py".

I used OpenCV for gathering the images from webcam and feed them into a Deep Learning model which will classify whether 
the person’s eyes are ‘Open’ or ‘Closed’. The approach I will be using for this Python project is as 
follows :

	Step 1 – Take image as input from a camera.

	Step 2 – Detect the face in the image and create a Region of Interest (ROI).

	Step 3 – Detect the eyes from ROI and feed it to the classifier.

	Step 4 – Classifier will categorize whether eyes are open or closed.

	Step 5 – Calculate score to check whether the person is drowsy.

The CNN model architecture consists of the following layers:
	* Convolutional layer; 32 nodes, kernel size 3
	* Convolutional layer; 32 nodes, kernel size 3
	* Convolutional layer; 64 nodes, kernel size 3
	* Fully connected layer; 128 nodes

Make sure the necessary python libraries are installed correctly.

Used Libraries :-     	* OpenCV (face and eye detection)
			* os
			* keras (to build our classification model)
			* numpy
			* pygame (to play alarm sound)
			* tensorflow (keras uses TensorFlow as backend)
			
		
