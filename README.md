# OpenGL-CPP
Discovering computer graphics with modern OpenGL and C++
</br>
Includes Linear Algebra
</br>



## Setting up the dev env for Linux
<h5>Install the compiler:</h5> 
<code>sudo apt update</code></br>
<h5>Install GCC, G++, and Make:</h5>
<code>sudo apt install build-essential</code></br>
<h5>Install GDB debugger:</h5>
<code>sudo apt install gdb</code></br>
</br>

<h5>OpenGL and GLEW:</h5>

<code>sudo apt-get install libglew-dev</code></br>
<code>sudo apt-get install libglfw3 libglfw3-dev</code>
<code>sudo apt install libglu1-mesa-dev freeglut3-dev mesa-common-dev</code>

<h5>SDL 2 and supporting libraries:</h5>
<code>sudo apt install libsdl2-dev libsdl2-2.0-0</code>
<h5>SDL Image:</h5>
<code>sudo apt install libjpeg-dev libwebp-dev libtiff5-dev libsdl2-image-dev libsdl2-image-2.0-0</code>
<h5>SDL True Type Fonts:</h5>
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
<li>Press [Control] + [Shift] + [p]. In the resulting requester, type in c/c++ make and then select “C/C++ Make: INIT Project” from the list.
<li>Select C++
<li>Setting up the libraries for <b>linking</b> to the project. After "LDFLAGS":
<code>-lSDL2 -lGL -lGLEW</code>
<li>To support proper debugging with symbols, add -g at the end of the “CXXFLAGS” line.
</br>

Type <code>make</code> in cmd prompt and hit [Enter]

See: https://www.paulbarrick.com/game-devlopment/game-development-on-linux-using-vscode-sdl2-and-opengl/