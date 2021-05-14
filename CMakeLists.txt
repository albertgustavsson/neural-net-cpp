cmake_minimum_required(VERSION 3.0)

project(NeuralNet)
set(CMAKE_CXX_STANDARD 11)

add_library(NeuralNet NeuralNet.cpp)
target_include_directories(NeuralNet PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})

add_subdirectory(examples)

add_subdirectory(external)