# Configuration of ROS2 (GUI) inside Docker with VSCode

## Installation

<details>
<summary><b> Windows </b></summary>
   
1. &nbsp; Download XLaunch Server from https://sourceforge.net/projects/vcxsrv/ and install.
2. &nbsp; Download Docker Desktop from https://docs.docker.com/desktop/install/windows-install/ and install.
3. &nbsp; Download Visual Studio Code from https://code.visualstudio.com/download and install.
4. &nbsp; Open VS Code and install an extension (shortcut CTRL+SHIFT+X) with the name "Remote Development".
5. &nbsp; Download [repository](https://github.com/Jakubach/ros2_docker_code):\
  a) &nbsp; in web browser:\
     &nbsp; &nbsp; &nbsp; click a button `Code --> Download ZIP` and unzip,\
  b) &nbsp; or in the Command Window:\
     &nbsp; &nbsp; &nbsp; use command: &nbsp; `git clone https://github.com/Jakubach/ros2_docker_code.git`

</details>


<details>
<summary><b>Ubuntu </b></summary>

1. &nbsp; Download Docker Engine, instruction: https://docs.docker.com/engine/install/ubuntu/#install-using-the-repository
2. &nbsp; Optionally, you can follow a post-installation steps from Docker documentation:\
   &nbsp; https://docs.docker.com/engine/install/linux-postinstall/
3. &nbsp; Download and install Visual Studio Code with command: &nbsp; `sudo apt-get install code`
4. &nbsp; Open VS Code and install an extension (shortcut CTRL+SHIFT+X) with the name "Remote Development".
5. &nbsp; Download [repository](https://github.com/Jakubach/ros2_docker_code):\
  a) &nbsp; in web browser:\
     &nbsp; &nbsp; &nbsp; change branch to Ubuntu, click a button `Code --> Download ZIP`, unzip,\
  b) &nbsp; or in the Terminal:\
     &nbsp; &nbsp; &nbsp; use command: &nbsp; `git clone https://github.com/Jakubach/ros2_docker_code.git -b Ubuntu`

</details>

## Running ROS

<details>
<summary><b> Windows </b></summary>

1. &nbsp; Run XLaunch Server with default settings.
2. &nbsp; Run Docker Desktop (in the background).
3. &nbsp; Run VS Code and open a directory `ros2_docker_code/src`, follow the bellow screen.

![Alt text](https://images2.imgbox.com/81/14/L3HKlegP_o.png)

The first time you run it, you may need to wait a little longer for the necessary software to download and install.

</details>


<details>
<summary><b>Ubuntu </b></summary>

1. &nbsp; Run Docker Engine with command `sudo systemctl start docker` (may not be necessary).
2. &nbsp; Run VS Code and open a directory `ros2_docker_code/src`, follow the bellow screen.

![Alt text](https://images2.imgbox.com/81/14/L3HKlegP_o.png)

The first time you run it, you may need to wait a little longer for the necessary software to download and install.

</details>
