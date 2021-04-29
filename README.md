# Mouse-Control-System-Using-Hand-Gestures

 1.INTRODUCTION 

 Gesture is performed by the user according to the function he needs to be performed in System. By using these model users can control the mouse with gestures performed by user Infront of web camera.
So, purpose of the model is to interact with machines like computers without any sensors or microprocessors, to control the mouse functions and give the information that is required to perform the function. We make use of the in-built camera or webcam to capture the gestures performed by the user as input and perform the corresponding functions given to the system. We capture the real time feed from the camera, convert the video into a number of image frames to process them, extract different parameters from the image and finally perform the respective mouse operations according to detected gestures.

2.SYSTEM ARCHITECTURE
The purpose of these model is to develop an interaction between computer and user. The model is composed of a web cam which captures real-time video. Following the block diagram (1.a) depicts the working of the model. The system captures frames using the webcam and then we use OpenCV2 to processes the captured frames over a sequence of digital image processing libraries to convert the images into grey scale for easy recognition of gestures

3.ALGORITM
3.1 Training Data
We import the required packages for the training the dataset. we create path for dataset to tarin the model. The image will be processed into gray black for recognition by the model.
3.1.1 Trained Dataset
  The dataset images are converted into gray black images.

3.1.2 Saving images to our model
 
Saving images to our model

3.1.3 Model Loss and Accuracy
 
Chart -1: Model loss and Accuracy.
In the above image the graph represents the loss data, accuracy and validation data. The red line represents Accuracy validation, blue line represents train loss, orange line represents validation loss. 
 
The accuracy of trained data is 99.97% and the loss accuracy is 0.03 %.

4.EXISTING SYSTEM
The existing system consists of had glove which is implemented using sensors and microcontroller. The glove is connected to the system using cable, without the cable connection the glove cannot be connected to the system.
Sensors like flex, contact,3-axis Accelerometer are used for gesture recognition. Sensors are connected to microcontroller like Arduino microcontroller will receive the values and from the sensors that is connected to glove.

5.METHODOLOGY
In order to achieve the mouse courser control, we used the following algorithm, based on hand gesture recognition.
Step 1: Acquiring Real time video from web camera
Step 2: Converting video into frames and into gray style images.
Step 3: Recognizing the hand gestures.
Step4: Performing the mouse functions
Our strategy is to utilize the built-in webcam of a computer, for capturing hand gestures and process them to perform the action. 
The system captures frames using the webcam and use opencv2 to processes the captured frames over a sequence of digital image processing libraries to convert the images to grey scale for easy recognition of fingers.  The model recognizes different hand gestures given by user and perform the actions. The proposed model is primarily based on machine learning and makes use of CNN (Convolution neural network) for processing, classification, segmentation of the captured images

6.EXPERIMENTAL RESULTS
The proposed Model was implemented in Python using OpenCV Library. It is trained with different hand gestures to control the Mouse functions in Operating System using CNN (Convolutional Neural Network). The purpose of CNN is to train the model. Cursor movement was performed by using Symbol “One”, Left click functions were performed using Symbol “Two”, Right click functions were performed using symbol “Five”.
When the symbol one is recognized, camera captures the image and process the image for hand gestures and perform the mouse cursor movement assigned by using python libraries. Model is trained with 860 images of hand gestures. The accuracy of training is 99.59%. The drawback while recognizing the hand gesture is if any object other than hand gestures are in the frame during capture the model was not able to perform the actions.

7.CONCLUSION AND FUTURE WORK
Therefore, in a nutshell, the proposed system is used to control the mouse to perform the basic mouse capabilities using a just a straight up web camera or one that’s attached to the computer. By doing so we were able to perform most of the mouse functions like cursor movement, selection of the icons, right/left clicking, double clicking and scrolling. 
 Analysing the results, we assume that if the algorithms were able to work in all environments, then our system will work even more efficiently, especially environments involving contrasting background and illuminance level. 
This system can be very useful in presentations, designing and for controlling different types of games and other applications. It can also reduce hardware cost by eliminating the use of mouse. This can also be of great help for the differently-abled, as they might not be able to use the conventional mouse like the others.
 In the future, we are planning to add even more features such as dragging and resizing windows, zooming in and out by pinching in, interaction within multiple windows over multiple applications etc. We have to decrease the overall response time of the system so that it can entirely replace the conventional mouse.
Also, we look forward in making it even more user-friendly by letting the user define their own gestures according to their preference.

8.References
*	“Real-time motion-based hand gestures recognition from time-of- flight video”. Signal Process. Syst. 2017, 86, 17–25. Published by Molina, Paulo and Martínez.
*	“Hand Gesture Recognition” Int. J. Recent Technol. Eng. 2019, 7 ,54–59. Published by Prakash J, Gautam, U.K.
*	“Real-time Hand Tracking Using Kinect”, International Conference on Digital Signal Processing, Tokyo, Japan, 25–27 February 2018. Published by Xi, C. Chen, J. Zhao, C. Pei, Q. Liu, L.
*	Pattern Recognition, finger and hand pose estimation technique for real-time hand gesture recognition. 2016, 49, 102–114. Published by Zhou, Y.; Jiang, G.; Lin, 
*	“A real time hand gesture recognition system using motion history image,” Proc. IEEE Conf. Signal Processing Systems (ICSPS),2010. Published by Chaung Hsieh, Hua Lieu, & D. Lee.
*  “Real Time Static & Dynamic Hand Gesture Recognition,”            International Journal of Scientific & Engineering Research, Vol. 4, Issue3, March 2013, published by P.S. Neethu
