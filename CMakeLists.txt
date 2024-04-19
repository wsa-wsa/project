cmake_minimum_required(VERSION 3.19)
project(project)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(project
        test.cpp)
