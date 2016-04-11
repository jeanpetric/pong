# Basic pong

A simple toy game developed in SDL.


## Linux (Debian/Ubuntu)
	Install packages: sudo apt-get install libsdl1.2debian libsdl1.2-dev libsdl2-dev libsdl2-image-dev
	Compile: g++ --std=c++11 pong.cpp `pkg-config --cflags --libs sdl2` -lSDL2 -lSDL2_image -o pong_lin
	
## Windows
	In great details explained here:
	    SDL base: http://lazyfoo.net/tutorials/SDL/01_hello_SDL/windows/index.php
	    SDL image (to load the dot and paddle): http://lazyfoo.net/tutorials/SDL/06_extension_libraries_and_loading_other_image_formats/windows/index.php
	Also, you can find pong_win.zip file with everything already prepared (in Code::Blocks)
	
## Mac OS X
	Explained here:
	    SDL base: http://lazyfoo.net/tutorials/SDL/01_hello_SDL/mac/index.php
	    SDL image (to load the dot and paddle): http://lazyfoo.net/tutorials/SDL/06_extension_libraries_and_loading_other_image_formats/mac/index.php
