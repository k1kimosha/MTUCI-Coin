[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
> This is project work on [CryptoNote](https://github.com/cryptonotefoundation/cryptonote)

# Build

## On *nix
Dependencies: GCC 4.7.3 or later, CMake 2.8.6 or later, and Boost 1.55.

You may download them from:

+ http://gcc.gnu.org/
+ http://www.cmake.org/
+ http://www.boost.org/
+ Alternatively, it may be possible to install them using a package manager.

To build, change to a directory where this file is located, and run `make`. The resulting executables can be found in `build/release/src`.

Advanced options:

+ Parallel build: run `make -j<number of threads>` instead of `make`.
+ Debug build: run `make build-debug`.
+ Test suite: run `make test-release` to run tests in addition to building. Running `make test-debug` will do the same to the debug version.
+ Building with Clang: it may be possible to use Clang instead of GCC, but this may not work everywhere. To build, run `export CC=clang CXX=clang++` before running `make`.

## On Windows
Dependencies: MSVC 2013 or later, CMake 2.8.6 or later, and Boost 1.55. You may download them from:

+ http://www.microsoft.com/
+ http://www.cmake.org/
+ http://www.boost.org/

To build, change to a directory where this file is located, and run theas commands:
```
mkdir build
cd build
cmake -G "Visual Studio 12 Win64" ..
```
And then do Build. Good luck!

# About us

We are a team of enthusiasts who decided to explore what blockchain is in practice. We created this fork for evaluation purposes only and do not make any claims at the moment.