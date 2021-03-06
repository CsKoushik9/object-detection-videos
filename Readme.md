## Installation

``` bash
# For CPU
pip install tensorflow
# For GPU
pip install tensorflow-gpu
```

The remaining libraries can be installed on Ubuntu 16.04 using via apt-get:

``` bash
sudo apt-get install protobuf-compiler python-pil python-lxml
sudo pip install jupyter
sudo pip install matplotlib
```
Install instructions for MAC OS X:
```
brew install protobuf
```
Alternatively, users can install dependencies using pip:

``` bash
sudo pip install pillow
sudo pip install lxml
sudo pip install matplotlib
sudo pip install opencv-python
```
### Compiling the protocol buffers
`protoc object_detection/protos/*.proto --python_out=.`


## Running the script

` python run.py `

I've used a video from the pad.ma

This script can be used for any video.

### While running for the first time, it will take time to download the pre-trained model. 

## This is one of the frames extraced from the video. 
![Test Images](https://github.com/Nikhil-Kasukurthi/object-detection-videos/blob/master/test_image.png?raw=true)
