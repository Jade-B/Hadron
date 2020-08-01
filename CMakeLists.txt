cmake_minimum_required(VERSION 3.18)
project(Hadron)

set(CMAKE_CXX_STANDARD 14)

add_library(Hadron SHARED library.cpp library.h)