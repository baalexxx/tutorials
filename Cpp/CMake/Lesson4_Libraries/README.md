#CMake tutorial - lesson 4 - Libraries
This the fundamental lesson. You will compile: static library, shared library and header only library. After that executable program that uses these libraries. Header only library isn't exactly library, because it only contains header files without binary artifacts. It is typical type of library for template classes artifacts.

Linux, OSX: Run command to generates Makefile files (assumed that you are in sibling directory of Code directory):
```
CMake ../Code
```
To compile:
```
make
```

#Target of this lesson
After this lesson you will know how to:
- compile static, shared and header only libraries,
- provide an external API of libraries,
- split an external API with internal header files,
- how to link targets.


*Author: Marcin Serwach*
*Tutorial: [https://github.com/iblis-ms/tutorials/tree/master/Cpp/CMake](https://github.com/iblis-ms/tutorials/tree/master/Cpp/CMake)*
