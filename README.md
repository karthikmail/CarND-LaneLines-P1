# **Finding Lane Lines on the Road** 

### Reflection

This is completely a new learning for me, there were lot of prerequisites i had to do while taking this first project. Because of the prerequisites i was not able try everything on time. I would like to redo this project with more ideas and videos (i do have my own videos to test on). Also, have referred some available solutions to do this. But now got hold of the basics and prerequisites so would be more effective in the upcoming lessons and projects. On the whole a great start and got my full attention to it. 

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

The tools i have used are

1) Grayscaling
2) Canny Edge Detection
3) Gaussian Smoothing
4) Region Of Interest Selection
5) Hough Lines detection

All this added together with thickness gives me a proper line, which are then drawn on the line segments on the image. THe line segments are detected as left and righ lane. Then the slope is set on the line segments. Once that pipeline is done i have tested the same pipeline on various images (you can check them on images_output folder). Also, the working pipeline was tested on the video streams and those are available on test_videos_output folder. The extra challenge alone did not work as expected, the output video available on the folder is without the left and right lane detection.


### 2. Identify potential shortcomings with your current pipeline

The shortcomings i feel

1) The line does not fall correctly on the detected line segments
2) Videos with bit of dark lighting does not get recognised 
3) Challenge video needs some fixing


### 3. Suggest possible improvements to your pipeline

1) Line segments are should be properly identified and drawn 
2) Convert dark videos to proper RGB to detect the lanes (Current one doesnt work on night videos)

