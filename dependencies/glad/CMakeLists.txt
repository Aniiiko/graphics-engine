cmake_minimum_required(VERSION 3.30.1)  # CMake version check
project(glad)                           # Create project "glad"


add_library(glad)
target_sources(glad PRIVATE src/glad.c)
target_include_directories(glad PUBLIC include)