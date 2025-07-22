cmake_minimum_required(VERSION 3.10)
project(stb LANGUAGES C CXX)

set(STB_INCLUDE_DIR ${CMAKE_CURRENT_SOURCE_DIR})

add_library(stb INTERFACE)
target_include_directories(stb INTERFACE ${STB_INCLUDE_DIR})