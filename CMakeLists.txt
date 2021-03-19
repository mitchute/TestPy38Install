cmake_minimum_required(VERSION 2.8.9)
project (hello)
add_executable(hello helloworld.cpp)
find_package(PythonInterp 3.8 REQUIRED) # just like E+ does
find_package(PythonLibs 3.8 REQUIRED)  # just like E+ does
message("${PYTHON_EXECUTABLE}")
message("${PYTHON_INCLUDE_DIRS}")
