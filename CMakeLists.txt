cmake_minimum_required(VERSION 3.17)
project(hacklib-patternscanner)

set(CMAKE_CXX_STANDARD 23)
add_library(hacklib-patternscanner STATIC
        ExeFile.cpp
        ExeFile_WIN32.cpp
        PatternScanner.cpp
        Memory_WIN32.cpp)
