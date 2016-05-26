Before building this X11 Simple OpenGL demo, you should install the following libraries first.

sudo apt update

# INSTALL apt-file

apt-file is a command line tool for searching files in packages for the APT package management system.

sudo apt install apt-file
sudo apt-file update

# INSTALL DEV TOOLS
sudo apt install build-essential

# INSTALL LibX libraries and MESA dev Libraries
sudo apt install libx11-dev
sudo apt install mesa-common-dev
sudo apt install libglu1-mesa-dev
sudo apt install mesa-utils

# INSTALL GLEW
sudo apt install build-essential libxmu-dev libxi-dev libgl-dev libosmesa-dev git
sudo apt install libglew-dev

# INSTALL Library (SDL2, GLUT, etc...)
sudo apt install libsdl2-dev

# INSTALL GLXOSD (FPS Monitor)
sudo apt-add-repository -y ppa:nickguletskii200/glxosd && sudo apt update && sudo apt install -y glxosd glxosd-libs-libsensors-support-amd64 glxosd-libs-libsensors-support-i386

Then just run the *make* command.

Have fun!