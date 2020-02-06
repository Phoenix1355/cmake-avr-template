<h1 align="center">AMS-Template</h1>

<div align="center">

A template for AMS that uses CMake to build and upload the files to the Arduino.

</div>

## Setup

### MacOS (Homebrew)

The required dependency `<avr/io.h>` comes with the `avr-gcc` package which can be installed using homebrew:

```bash
brew install avr-gcc
```

### Linux

If you're linux and you don't know how to install the required dependecies, you should probably switch (back) to windows or MacOS...

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
