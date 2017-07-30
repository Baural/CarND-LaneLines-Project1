# **Finding Lane Lines on the Road**

## Writeup Template

### You can use this file as a template for your writeup if you want to submit it as a markdown file. But feel free to use some other method and submit a pdf if you prefer.

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

First step I followed with instruction in Readme.md Starter Kit Installation
* Second step I watched all lessons about Anaconda and Jupyter
* I have had some problem with packeges in evironment
* Ashutosh recommended me reinstall envirinment
* Third I made a  git clone https://github.com/udacity/CarND-Term1-Starter-Kit-Test.git
After the I have open a directory  CarND-Term1-Starter-Kit-Test
* I activated my new environment
* 


[//]: # (Image References)

[image1]: ./examples/grayscale.jpg "Grayscale"

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. First, I converted the images to grayscale, then I showed a picture of test image. Second, I run code in Tensorflow Block for seeing who it calculate.
Third I install a moviepy and added extra ffmpeg components in code. Fourth I converted test mp4 to test_out.mp4 with YUV color. The YUV color space could to find yellow left lane.
Fifth I showed a results with HTML in Jupiter notebook.


![alt text][image1]


### 2. Identify potential shortcomings with your current pipeline


One potential shortcoming would be what would happen when tensorflow does not working with new packeges Python 3.6 in Mac. It was a great experience for me to “repair system”. Now I know how important to use special environments.



### 3. Suggest possible improvements to your pipeline

A possible improvement would be to use in Jupiter notebook all exercise for detecting edges for example.


