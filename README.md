# LPC-Toolkit
A toolkit of Max objects to use real-time linear predictive coding in creative projects

This project was initially developed in 2007 at Stanford's Center for Computer Research in Music and Acoustics (CCRMA), but it hasn't seen much attention since then. Contributions are welcome.

For more information please visit http://markcartwright.com/projects/lpc-toolkit

Mark Cartwright
mcartwright@gmail.com

## Development

Make sure you have CMake installed

```sh
git clone <repository URL> --recurse-submodules
# if you forget the flag, you can instead run:
# git submodule update --init --recursive
mkdir build
cd build
cmake ..
cmake --build .
```