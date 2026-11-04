cmake_minimum_required(VERSION 3.21)

project(NicoInputBuffer)

add_library(${PROJECT_NAME} SHARED
    src/main.cpp
)

setup_geode_mod(${PROJECT_NAME})

