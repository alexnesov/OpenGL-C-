# OpenGL-CPP
Discovering computer graphics with modern OpenGL and C++
</br>
Includes Linear Algebra
</br>



# Setting up the dev env for Linux
Compiler:
<code>sudo apt update</code></br>
Install GCC, G++, and Make:
</br>
<code>sudo apt install build-essential</code></br>
Install GDB debugger:
<code>sudo apt install gdb</code></br>


<code>sudo apt-get install libglew-dev</code></br>
<code>sudo apt-get install libglfw3 libglfw3-dev</code>
<code>sudo apt install libglu1-mesa-dev freeglut3-dev mesa-common-dev</code>

<h4>SDL 2 and supporting libraries:</h4>
<code>sudo apt install libsdl2-dev libsdl2-2.0-0</code>
</br>
<code>sudo apt install libjpeg-dev libwebp-dev libtiff5-dev libsdl2-image-dev libsdl2-image-2.0-0</code>
</br>
<code>sudo apt install libfreetype6-dev libsdl2-ttf-dev libsdl2-ttf-2.0-0</code>
</br>




## Visual Studio Code configuration:
Install "C/C++ Makefile Project" from Extensions (CTRL + SHIFT + X)
</br>
Install </b>Code Runner</b>
</br>
Code Runner allows you to run a piece of code without having to use the terminal to build your application.
</br>

Place main.cpp in a <i>src</i> folder

### Set up the make file for compiling:
Press [Control] + [Shift] + [p]. In the resulting requester, type in c/c++ make and then select “C/C++ Make: INIT Project” from the list.


See: https://www.paulbarrick.com/game-devlopment/game-development-on-linux-using-vscode-sdl2-and-opengl/