cmake_minimum_required(VERSION 3.10)

project(cmake-simple)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

file (GLOB_RECURSE srcs src/*.cpp src/*.h)

add_executable(cmake-simple ${srcs})


