cmake_minimum_required(VERSION 3.10)

project(console_lib)
include_directories(include)

add_library(console_lib STATIC
    src/test.cpp
)
