cmake_minimum_required(VERSION 3.6)
project(try1)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp CppClient.cpp CppServer.cpp)
add_executable(try1 ${SOURCE_FILES})