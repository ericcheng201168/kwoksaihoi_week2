cmake_minimum_required(VERSION 3.2)
project(kwoksaihoi_week2)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(kwoksaihoi_week2 ${SOURCE_FILES} uppercaser.h uppercaser.c)