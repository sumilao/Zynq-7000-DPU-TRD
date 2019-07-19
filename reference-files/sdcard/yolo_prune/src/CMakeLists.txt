cmake_minimum_required(VERSION 3.8)
project(src)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        image.h
        main.cpp)

add_executable(src ${SOURCE_FILES})