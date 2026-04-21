cmake_minimum_required(VERSION 2.8)
project(A_plus_B CXX)

# Keep it minimal and widely compatible
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(code solution.cpp)
