<<<<<<< HEAD
# Prerequisites

* GCC C++ compiler, aka g++ (tested with 4.x and 5.x)
* GNU Make (3.81 and newer were tested but older probably work)
* CMake 2.6 or newer (the most recent available is recommended)
* SWIG 2.0 or newer (3.0 or newer is recommended)
* Python 2.5 or newer (Python 3 is **not** supported)
* Python libraries and headers (usually in ```python-dev``` or
  ```python-devel```, included in Windows Python installer)
* BioPython 1.57 or newer
* NumPy 1.3 or newer

## Linux

On Linux use the package manager to install the prerequisites (alternatively
```pip``` for BioPython and NumPy).

## Windows

On Windows download the prerequisites from their respective sites:

* GNU Toolchain - <http://tdm-gcc.tdragon.net/download/> (only TDM has proven
  to work)
* CMake - <https://cmake.org/download/>
* SWIG - <http://www.swig.org/download.html>
* Python - <https://www.python.org/downloads/windows/>
* NumPy and BioPython - <http://www.lfd.uci.edu/~gohlke/pythonlibs/>

Make sure all the following binaries are available to be called from the
command prompt:

```
g++
make
cmake
swig
python
```

Use the ```where``` command to confirm that correct binaries are in use. This
is important because some programs ship with their own version of GCC toolchain
and make it available in ```PATH```. Reorder paths in the ```PATH``` variable
to make sure you use the TDM toolchain.

# Compiling

Open up console/terminal/command prompt. Then navigate to the extracted PyRy3D
root directory and execute the platform-specific commands given below.
Success is given by 100% progress and no errors below it.

## Linux

```
cd Modules/Simul/cpp
./compile
```

## Windows

```
cd Modules\Simul\cpp
compile
```

Double-clicking on ```compile.cmd``` in ```Modules\Simul\cpp``` works as well.
=======
# pyry3d_main
>>>>>>> c0076e2127e94a8d9e0db47513a2936aa1eae41f
