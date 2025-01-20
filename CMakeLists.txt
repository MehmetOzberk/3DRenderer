# Minimum required CMake version
cmake_minimum_required(VERSION 3.10)

# Project name
project(3DRenderer)

# Set C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add the executable
add_executable(3DRenderer 3DRenderer/main.cpp)