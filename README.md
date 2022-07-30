# Face-Detection-in-Images-using-HAAR-Classifier

Generally, Face Recognition is a method of identifying or verifying the identity of an individual by using their face.
Face detection is generally the first step towards many face-related applications like face recognition or face verification. 
But, face detection has very useful applications.


OpenCV is a video and image processing library and it is used for image and video analysis, like facial detection,
license plate reading, photo editing, advanced robotic vision, and many more.

HAAR cascade is algorithm that is capable of detecting objects in images, regardless of their location and scale in an image.
One of the primary benefits of Haar cascades is that they are just so fast — it’s hard to beat their speed. 
The downside to Haar cascades is that they tend to be prone to false-positive detections, require parameter tuning when being applied for inference/detection,
and just, in general, are not as accurate as the more “modern” algorithms we have today.

The detectMultiScale function detects the faces in the images. Its parameters are as follows:
The grayscale image in which faces are to be detected.<br>
scaleFactor - Since some faces may be closer to the camera, they would appear bigger than the faces in the back.<br>
The scale factor compensates for this.<br>
The detection algorithm uses a moving window to detect objects.<br> 
minNeighbors defines how many objects are detected near the current one before it declares the face found
. minSize, meanwhile, gives the size of each window.
