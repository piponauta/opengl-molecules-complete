opengl-molecules
================

## Build

To compile and run, once cloned go to the repository directory and run:

``` sh
cmake -S . -B build
cmake --build build -j 8
```
You can set the number of cores used to build changing the `-j` argument.
Onces built you can run
``` sh
# You must change to the directory so the program will find the textures, shaders and molecule files.
cd build/opengl-molecules
./opengl-molecules
```

## License

MIT
