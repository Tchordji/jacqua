## Robot Package Template

This is a GitHub template. You can make your own copy by clicking the green "Use this template" button.

It is recommended that you keep the repo/package name the same, but if you do change it, ensure you do a "Find all" using your IDE (or the built-in GitHub IDE by hitting the `.` key) and rename all instances of `jacqua` to whatever your project's name is.

Note that each directory currently has at least one file in it to ensure that git tracks the files (and, consequently, that a fresh clone has direcctories present for CMake to find). These example files can be removed if required (and the directories can be removed if `CMakeLists.txt` is adjusted accordingly).

ajouter les lignes suivantes à .bashrc :
source /opt/ros/jazzy/setup.bash
source ~/dev_ws/install/setup.bash
export LIBGL_ALWAYS_SOFTWARE=1

liste des librairies à installer : 
sudo apt install ros-jazzy-xacro
sudo apt install ros-jazzy-joint-state-publisher-gui
sudo apt install gz-harmonic
sudo apt install twist_stamper
sudo apt install ros-jazzy-ros2-control
sudo apt install ros-jazzy-ros2-controllers
sudo apt install ros-jazzy-gz-ros2-control
sudo apt install joystick 
sudo apt install jstest-gtk 
sudo apt install evtest