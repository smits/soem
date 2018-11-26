# SOEM ROS Catkin Package

## To compile for ROS

Clone the Package to the catkin workspace

Source the ROS workspace
```
catkin_make
```
--------------------------------------------------------------


## To compile for linux:

go to project directory
```
source ./setup.sh linux

make all
```
Please read the doxygen documentation in doc/html/index.html

--------------------------------------------------------------

## To complie for windows:

go to project directory 

Build soem libary make_libsoem_lib.bat <Path to MSVC VC> <arch>

Ex: make_libsoem_lib.bat "C:\Program Files (x86)\Microsoft Visual Studio 10.0\VC" x86

Build test folder make_test_win32.bat <Path to MSVC VC> <arch>

Ex: make_test_win32.bat "C:\Program Files (x86)\Microsoft Visual Studio 10.0\VC" x86

Test: slavinfo.exe <wpcap device name>. sllaveinfo.exe will print the \Device\NPF_{xxxxxx}'s
Ex. slaveinfo.exe \Device\NPF_{735D4B45-68D6-47A6-B826-E0DA26AC761A}

