# cmake_minimum_required(VERSION <specify CMake version here>)
project(Projet_Concurrence)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Projet_Concurrence ${SOURCE_FILES})