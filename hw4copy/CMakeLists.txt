cmake_minimum_required(VERSION 3.3)
project(hw4)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    hw4.c
    shell.c
    shell.h)

add_executable(hw4 ${SOURCE_FILES})