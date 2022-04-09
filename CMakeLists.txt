cmake_minimum_required(VERSION 3.20)
project(untitled)

set(CMAKE_CXX_STANDARD 14)

add_executable(untitled main.cpp Base.h Rectangle.h Rectangle.cpp Ellipse.cpp Ellipse.h)
