# Bird Detection using OpenCV


In the last decade, it has become much easier to detect objects/animals using deep learning algorithms with just a few lines of Python code. We will learn how to detect a bird in any video/webcam and return the number of birds in each frame in this tutorial.
First and foremost, we will import key libraries such as OpenCV and load the Cascade Classifier (XML File). We'll utilize a web cam or a downloaded video of birds to take video.
Requirements-
Jupyter Notebook
OpenCV
Cascade Classifier

First, we'll see if you have the necessary Python libraries loaded on your system and import them.

We'll then build the class DetectBirds and load the cascade classifier. We'll keep capturing video until the running mode is true [while(TRUE)], at which point we'll stop. 
Then we'll convert each frame to grayscale and look for birds in the resulting image. 
Following that, we will count the birds that have been spotted, and finally, we will print the birds that have been discovered in each frame.

We also drew a rectangle around the observed birds and displayed the resulting frame in the preceding code.
When everything is finished, the following code run to release the capture and return to take another.


We'll then load the video in which we'll perform the detection.

We can see that we were successful in detecting birds in the video, as evidenced by the green rectangle and printed  the number of birds in each frame.
