cmake_minimum_required(VERSION 3.22)
project(cpp_primer)

set(CMAKE_CXX_STANDARD 11)

add_subdirectory(1_GettingStarted)
add_subdirectory(2_VariablesAndBasicTypes)

add_executable(cpp_primer main.cpp)
