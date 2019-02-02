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
2. Tensorflow needs correct GPU drivers, cuda toolkit and cudaNN library in the system. Tensorflow 1.12.0 works only with python 3.5 or 3.6(not 3.7), [cuda toolkit 9.0.176](https://developer.nvidia.com/cuda-90-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exelocal) also install it's patches, Graphics driver 388.73 and [cudaNN 9.0 v.7.3.1](https://developer.nvidia.com/rdp/cudnn-archive)

	Note: As my system had 6 GB GTX1060 graphics card; Graphics driver 388.73(which came pre-installed in my system worked correctly. so, please use pre-installed driver, don't upgrade it otherwise it won't work atleast in my case it didn't). you need to copy cudann library into respective cuda toolkit installed folder and restart.
	
3. once it is installed run notebooks '04_basic_cnn_model_in_keras.ipynb' and '05_test_notebook_to_verify_gpu_setup.ipynb'. first notebook will train digit classifier if everything is setup correctly it will work without any error. while the second notebook will perform basic calculation on GPU explictly, so if `tensflow-gpu` is setup correctly then it will show you available GPU hardware list and perform calculation on them.

##Jupyter tips and tricks:
This section documents all the useful tips that would be helpful for beginners like me to increase their productivity in writing jupyter notebooks, which I wish I new when I started.

- read them from [here](https://github.com/JahanAjani/SelfDrivingCar/blob/master/jupyter_tips.md). 

Have fun!
If you find any bug please feel to send me PR to merge. Thanks in advance.


[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/0)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/0)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/1)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/1)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/2)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/2)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/3)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/3)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/4)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/4)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/5)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/5)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/6)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/6)[![](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/images/7)](https://sourcerer.io/fame/JahanAjani/JahanAjani/SelfDrivingCar/links/7)
