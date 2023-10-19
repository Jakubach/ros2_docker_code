# Configuration of ROS2 (GUI) inside Docker with VSCode

## Ubuntu 

Ubuntu guide is in official documentation:
https://docs.ros.org/en/humble/How-To-Guides/Setup-ROS-2-with-VSCode-and-Docker-Container.html

## Windows

#### 1. Install Xlaunch Server for displaying GUI:

https://sourceforge.net/projects/vcxsrv/

#### 2. Run Xlaunch Server and setup a display with port 0

#### 3. Follow steps from the official documentation using modified files for Windows.

Modified files for Windows are available withing this repository.
- Changed `DISPLAY` from X11 to Xlaunch
- Changed GPU access for compatibility with Windows (https://stackoverflow.com/questions/49589229/is-gpu-pass-through-possible-with-docker-for-windows)
