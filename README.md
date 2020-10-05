# lane-detection
This project is about lane detection using various algorithms and using python code

Advanced driving assistant systems, intelligent and autonomous vehicles are promising solutions to enhance road safety, traffic issues and passengers' comfort. 
Which requires advanced computer vision algorithms that demand powerful computers with high-speed processing capabilities. Keeping intelligent vehicles on the road until its destination, in some cases, remains a great challenge, particularly when driving at high speeds. 
The first principle task is robust navigation, which is often based on system vision to acquire rgb images of the road for more advanced processing. 

ALGORITHM USED IN OUR PROJECT: 
BIRDS EYE VIEW ALGORITHM
KALMAN FILTER ALGORITHM
HOUGH LINE TRANSFORM ALGORITHM
DISTORTION CORRECTION ALGORITHM
RANSAC ALGORITHM
CANNY ALGORITHM

1.The bird’s eye view is a vision monitoring system used in automotive ADAS technology that provides the 360-degree, top-down view. 
The main benefits of this system is to assist the driver in parking the vehicle safely. However, it can be used for lane departure and obstacle detection. 
This system normally includes between four and six fish-eye cameras mounted around the car to provide right, left, front and rear views of the car’s surroundings.

2.The kalman filter is a recursive state space model based estimation algorithm.  
This algorithm was basically developed for single dimensional and real valued signals which are associated with the linear systems assuming the system is corrupted with linear additive white Gaussian noise.

3.The linear Hough transform algorithm uses a two-dimensional array, called an accumulator, to detect the existence of a line described by .
Each element of the matrix has a value equal to the sum of the points or pixels that are positioned on the line represented by quantized parameters (r, θ).

4.In the methodology, we made use of the python library and its functions such as the canny function through which we achieved edge detection. 
Then we used the Hough transform technique that detected the straight lines in the image and identified the lane lines. We made use of the polar coordinates since the Cartesian coordinates don’t give us an appropriate slope of vertical and horizontal lines. Finally, we combined the lane image with our zero-intensity image to show lane lines.
