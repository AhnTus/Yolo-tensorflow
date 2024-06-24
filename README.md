# YOLO_tensorflow
### 1.Introduction

This is tensorflow implementation of the YOLO:Real-Time Object Detection

### 2.Usage

(1) direct usage with default settings (display on console, show output image, no output file writing)

	python YOLO_(small or tiny)_tf.py -fromfile (input image filename)

(2) direct usage with custom settings

	python YOLO_(small or tiny)_tf.py argvs

	where argvs are

	-fromfile (input image filename) : input image file
	-disp_console (0 or 1) : whether display results on terminal or not
	-imshow (0 or 1) : whether display result image or not
	-tofile_img (output image filename) : output image file
	-tofile_txt (output txt filename) : output text file (contains class, x, y, w, h, probability)

### 3.Requirements

- Tensorflow
- Opencv2


