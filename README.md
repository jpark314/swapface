Special thanks to Matthew Earl
original source: https://github.com/matthewearl/faceswap/blob/master/faceswap.py

This is a simple python script that reads in 2 images from the input url and replace faces from one image to another.

First, install python pip and install following pip libraries
* opencv2
* numpy
* dlib

Run with following command:
$ python swapface.py url1 url2

The output will result as output_#.jpg as # increases from 1.

In order to change the input files, comment out lines 196 and 197 and read sys.argv[1] and sys.argv[2]
directly to read_im_and_landmarks.
