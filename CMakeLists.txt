cmake_minimum_required(VERSION 2.7)
project(test_Azure)

set(CMAKE_BUILD_TYPE "Release")
set(CMAKE_CXX_FLAGS "-std=c++11")
set(CMAKE_CXX_FLAGS_RELEASE "-O3 -Wall -g")
add_executable(a hello_world.cpp)
