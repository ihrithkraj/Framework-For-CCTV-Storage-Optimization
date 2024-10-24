# Framework-For-CCTV-Storage-Optimization

Data Output: contains logfiles having data of objects detected and other relevent information assosiated with them.
Static-Website: Temporary website for displaying output.
Video-Outputs: Final output video after processing.

Distance calculation methods used:
Normal Distance: Gives the numerical measurement of how far apart objects or points are in two consecutive frames.
Euclidean Distance: Provides the Euclidean distance between two points in Euclidean space which is the length of a line segment between the two points.
Manhattan Distance: Provides the Manhattan distance which is the distance between two points measured along axes at right angles.
Discrete Cosine Transform: Provides a finite sequence of data points in terms of a sum of cosine functions oscillating at different points.

Python scripts:
Bounding_boxes.py: Code to detect object and create bounding box around them.
Eculedian_dist.py: Code to find Eucledian Distance between objects.
fileClear.py: Program to clear log files.
fileConverter.py: Program to convert output video files from one form to other form. (e.g. avi to mp4)
Main.py: Program to reduce storage space by implimenting the actual algorithm.
temp.py: back-up of Main.py file
