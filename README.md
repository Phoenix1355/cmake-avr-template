<h1 align="center">AMS-Template</h1>

<div align="center">

A template for AMS that uses CMake to build and upload the files to the Arduino.

</div>

## Setup

### MacOS (Homebrew)

The required dependency `<avr/io.h>` comes with the `avr-gcc` package which can be installed using homebrew:

```bash
brew tap osx-cross/avr
brew install avr-gcc
```

### Linux

If you're linux and you don't know how to install the required dependecies, you should probably switch (back) to windows or MacOS...

Or just install cmake gcc-avr and ninja-build (optional) and run the following from the root of your project

```bash
mkdir build && cd build
cmake ..
make upload_ams
```

or with ninja

```bash
mkdir build && cd build
cmake .. -GNinja
ninja upload_ams
```

### Windows

GL HF

### Usage

Build:

```bash
cmake --build ./build
```

Upload:

```bash
make -C build/ upload_ams
```
