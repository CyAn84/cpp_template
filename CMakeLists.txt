cmake_minimum_required(VERSION 3.12)

project(my_project LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 14)

add_executable(
    my_project
    src/main.cpp
)