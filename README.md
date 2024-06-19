# Simple Linux Driver

Simple Linux driver that copies the string "Hello world from kernel mode!" to the user space.

## Build

1. `make all` to compile the code
2. `sudo make load` to register the character device and add to /dev

## Clean

`make clean` removes temporary files from the directory

`sudo make unload` removes from /dev and unregisters the character device
