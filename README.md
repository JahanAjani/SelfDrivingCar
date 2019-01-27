# SelfDrivingCar
This repository contains all the work that I am doing for autonomous SDC to work. It includes image/video processing, machine learning techniques. The work is in progress, I am going to gradually update it.

## Installation:
1. install python 3.6.
2. Clone this repository on local machine.
3. open CMD from clone folder and create virtual environment `python -m venv sdc`
4. Activate virual environment: `sdc\Scripts\activate`
5. Run `pip install -r requirement.txt` to install all the dependency required for this project.

## Steps to run notebooks(.ipynb):
1. run `jupyter notebook`
2. open the desired notebook from the browser.

## steps to setup tensorflow:
1. Tensorflow has two variants - cpu and gpu, I have installed `tensorflow-gpu` in my system(already in requiremennt.txt so you don't have to manually install it.)
2. Tensorflow needs correct gpu drivers, cudaNN library in the system.
	My system has 6 GB GTX1060 graphics card, here's the list of versions which worked for me:
	a. Graphics driver 388.73(which came pre-installed in my system. use pre-installed driver, don't upgrade it.)
	b. Tensorflow ver which is installed is 1.12.0, which needs cudaNN 9.0 v.7.3.1, download and install it.
	c. Last is cuda toolkit as abov tensorflow supports cuda 9.0 only, install cuda toolkit 9.0.176 along with all the patches from nvidia website.
	note: you need to copy cudann library into respective cuda toolkit installed folder and restart.
3. once it is installed run notebooks '04_basic_cnn_model_in_keras.ipynb' and '05_test_notebook_to_verify_gpu_setup.ipynb'.
You will see it will run without error on GPU, this will ensure your setup is done correctly.

Have fun!
If you find any bug please feel to send me PR to merge. Thanks in advance.
