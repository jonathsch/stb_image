cmake_minimum_required(VERSION 3.10)
project(stbi LANGUAGES C VERSION 0.1.0)

set(PUBLIC_HEADERS include/stb.h)

add_library(stbi STATIC src/stb.c)
add_library(stbi::stbi ALIAS stbi)
target_include_directories(stbi PUBLIC "include")
