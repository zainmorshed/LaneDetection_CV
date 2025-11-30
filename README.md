Lane Detection and Tracking in Video using Computer Vision
​​

In this project, I developed a lane detection system using OpenCV and computer vision techniques to identify and track lane markings in video footage.
The goal was to create an automated system that could process road videos and detect lane boundaries in real time, a critical feature for autonomous vehicle systems.

Key components of the project:

Canny Edge Detection: I used the Canny edge detection algorithm to extract the most prominent edges in the video frames, focusing on lane markings and road boundaries.

Region of Interest (ROI): To optimize the detection process, I applied a region of interest (ROI) filter to focus on the area where the lanes are most likely to appear, reducing the impact of irrelevant background details.

Hough Line Transform: The Hough Line Transform was used to identify straight lines in the processed image, representing the lanes in the video footage.

Line Averaging: By implementing slope and intercept averaging techniques, I was able to smooth the lane detection process and eliminate noise in the results, ensuring the lane boundaries remained consistent throughout the video.

Real-time Processing: The system processes video frames in real time, displaying the lane markings superimposed on the original video to give immediate feedback on lane tracking.

​
