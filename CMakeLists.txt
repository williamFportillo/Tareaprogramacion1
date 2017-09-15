cmake_minimum_required(VERSION 3.8)
project(tareanum1)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.cpp Evaluador.h)
add_executable(tareanum1 ${SOURCE_FILES})