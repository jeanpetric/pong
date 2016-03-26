# Basic pong

A simple toy game developed in SDL.


Get SDL Debian: sudo apt-get install libsdl1.2debian libsdl1.2-dev libsdl2-dev libsdl2-image-dev

Compile: g++ pong.cpp \`pkg-config --cflags --libs sdl2\` -lSDL2 -lSDL2_image
