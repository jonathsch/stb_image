cmake_minimum_required(VERSION 3.10)
project(stb LANGUAGES C VERSION 0.1.0)

add_library(stb stb.c)
target_include_directories(stb INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/stb)