cmake_minimum_required(VERSION 3.6)
project(NiceRF_Service)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(NiceRF_Service ${SOURCE_FILES})