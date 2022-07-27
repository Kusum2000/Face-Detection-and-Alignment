# Face Detection and Alignment

Detect multiple faces from a single image using mtcnn and alignment of each detected face using a modified version of HOG Face alignment.

Multi-task Cascaded Convolutional Networks (MTCNN) is a framework developed for face detection and face alignment. It has a higher accuracy in detecting faces in various settings compared to HOG and other algorithms. It detects landmark locations such as eyes, nose, mouth and the bounded box of the faces in the image.

## Features

- Detect multiple faces in any direction, clarity and environment
- Customize the desired output image width and height
- Customize the required box size for the aligned image

## Requirements

- mtcnn
- cv2
- pyplot
- numpy
- imutils
