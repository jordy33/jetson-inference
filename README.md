### Install Jetson Inference

Previous Requirements

```
sudo apt-get upgrade -y
sudo apt-get update
sudo apt-get install git cmake
git clone https://github.com/dusty-nv/jetson-inference
cd jetson-inference
git submodule update --init
sudo apt-get install libpython3-dev python3-numpy
```

Configuring CMake
```
cd jetson-inference    # omit if pwd is already jetson-inference from above
mkdir build
cd build
cmake ../
```

Installing support glxgears

```
sudo apt-get install mesa-utils
glxgears
```
