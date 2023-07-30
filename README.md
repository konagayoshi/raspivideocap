これはCoyote009のraspiviceocapをforkしたものです。

# raspivideocap
C++ Camera capture library for raspberry pi camera v2

## Environment
raspivideocap was tested with the following environment
- Raspberry Pi OS Bullseye 5.10.63-v7+
- OpenCV 4.3.0

## Installation
1. Follow the [official installation instruction](https://docs.opencv.org/3.4.3/d7/d9f/tutorial_linux_install.html) to install OpenCV 3.4+ from the source code
2. Clone source code and install
```
> git clone https://github.com/konagayoshi/raspivideocap.git
> cd raspivideocap
> mkdir build
> cd build
> cmake ..
> make
> sudo make install
```
3. Test
```
# Goto raspivideocap directory
> cd test
> mkdir build
> cd build
> cmake ..
> make
> ./test_raspivideocap
```

## License
[GPLv2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)

