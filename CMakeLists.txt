cmake_minimum_required(VERSION 2.8.4)
project(webbench_1_5)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    debian/changelog
    debian/control
    debian/copyright
    debian/dirs
    debian/rules
    Makefile
    socket.c
    webbench.1
    webbench.c)

add_executable(webbench_1_5 ${SOURCE_FILES})