cmake_minimum_required(VERSION 3.8)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(cmake_example)

add_subdirectory(pybind11)
pybind11_add_module(cmake_example src/main.cpp)
