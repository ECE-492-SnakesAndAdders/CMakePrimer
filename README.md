# CMake Primer

## What does CMake do?
It manages the build process of a project. 

### What's a build process?
A build process involves taking your source code, which is written in a high level language like C or C++ and transforming it into an executable program or library that can be run by the machine

### Sweet! So what does CMake do again?
CMake helps automate and organize this process by generating platform-specific build files (like Makefiles or Visual Studio Project files) based on a configuration descrbed in a CMakeLists.txt
This means that CMake allows developers to write a single set of build instructions that can be used on different operating systems and with various build tools.

### What's in a CMakeLists.txt?
This file contains instructions on how to build the project, such as which source files to include, compiler options and dependencies

Our CMakeLists.txt has these 3 lines:

  cmake_minimum_required(VERSION 3.20.0)
  project(Hello) -> **naming our project**
  add_executable(Hello_cmake hello.cpp) -> **here, Hello is the name of our executable that will be generated and hello.cpp is the source file**

### Those are the basics. The CMake docs should be able to help you figure out your specific needs
